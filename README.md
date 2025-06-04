import { Button import React from "react";
} from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { Sparkles } from "lucide-react";

export default function RandomWebsite() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-indigo-500 to-purple-700 text-white p-6 flex flex-col items-center justify-center">
      <Card className="bg-white/10 backdrop-blur-lg rounded-2xl shadow-xl p-6 max-w-md w-full text-center">
        <CardContent>
          <div className="flex justify-center mb-4">
            <Sparkles size={48} className="text-yellow-300 animate-pulse" />
          </div>
          <h1 className="text-3xl font-bold mb-2">Welcome to the Random Zone</h1>
          <p className="text-lg mb-6">
            This is a random website. It doesn’t do much, but it looks cool.
          </p>
          <Button className="bg-yellow-400 hover:bg-yellow-300 text-black font-semibold">
            Do Nothing
          </Button>
        </CardContent>
      </Card>
    </div>
  );
}
