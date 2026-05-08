"use client"

import { useEffect, useMemo, useState } from "react"
import { AnimatePresence, motion } from "framer-motion"
import {
  Heart,
  Users,
  Moon,
  Sparkles,
  Shuffle,
  Copy,
  Star,
  Music2,
  Search,
  Smile,
} from "lucide-react"

export default function DeepTalksWebsite() {
  const questionData = {
    couple: [
      "Apa hal kecil yang paling bikin kamu merasa dicintai?",
      "Kapan terakhir kali kamu merasa benar-benar bahagia sama aku?",
      "Apa mimpi terbesar kita menurut kamu?",
      "Kalau kita ketemu lebih cepat, apa yang bakal terjadi?",
      "Apa love language kamu yang paling ingin dipahami?",
      "Kalau kita punya satu hari tanpa masalah, mau ngapain?",
    ],
    friendship: [
      "Momen paling memalukan kita apa?",
      "Kalau kita bikin bisnis bareng, bakal jualan apa?",
      "Apa first impression kamu ke aku dulu?",
      "Siapa yang paling mungkin jadi terkenal duluan?",
      "Apa chaos terbesar yang pernah kita buat?",
      "Kalau liburan dadakan sekarang, kita pergi ke mana?",
    ],
    self: [
      "Hal apa yang paling sering kamu sembunyikan dari orang lain?",
      "Apa versi terbaik dirimu menurut kamu?",
      "Kapan terakhir kali kamu bangga sama diri sendiri?",
      "Apa yang sedang ingin kamu maafkan?",
      "Apa yang paling bikin kamu capek akhir-akhir ini?",
      "Apa hal yang sebenarnya ingin kamu mulai lagi?",
    ],
    kids: [
      "Kalau kamu punya kekuatan super, mau jadi apa?",
      "Hewan apa yang paling lucu menurut kamu?",
      "Kalau bisa pergi ke luar angkasa, mau bawa siapa?",
      "Apa hal paling seru hari ini?",
      "Kalau monster baik itu ada, namanya siapa?",
      "Es krim rasa paling aneh yang pengen kamu coba apa?",
    ],
  }

  const categories = [
    {
      id: "couple",
      title: "Couple Talk",
      icon: Heart,
      gradient: "from-pink-400 via-rose-300 to-purple-300",
      desc: "Romantic and emotional conversations.",
    },
    {
      id: "friendship",
      title: "Friendship Talk",
      icon: Users,
      gradient: "from-sky-400 via-cyan-300 to-blue-300",
      desc: "Fun and chaotic friendship moments.",
    },
    {
      id: "self",
      title: "Self Reflection",
      icon: Moon,
      gradient: "from-violet-400 via-purple-300 to-indigo-300",
      desc: "Deep healing and mindful questions.",
    },
    {
      id: "kids",
      title: "Kids Talk",
      icon: Sparkles,
      gradient: "from-yellow-300 via-orange-200 to-pink-300",
      desc: "Creative and fun kids questions.",
    },
  ]

  const [activeCategory, setActiveCategory] = useState("couple")
  const [currentQuestion, setCurrentQuestion] = useState(questionData.couple[0])
  const [favorites, setFavorites] = useState([])
  const [darkMode, setDarkMode] = useState(false)
  const [search, setSearch] = useState("")

  useEffect(() => {
    const saved = localStorage.getItem("deeptalks-favorites")
    if (saved) setFavorites(JSON.parse(saved))
  }, [])

  useEffect(() => {
    localStorage.setItem("deeptalks-favorites", JSON.stringify(favorites))
  }, [favorites])

  const filteredQuestions = useMemo(() => {
    return questionData[activeCategory].filter((q) =>
      q.toLowerCase().includes(search.toLowerCase())
    )
  }, [search, activeCategory])

  const generateQuestion = () => {
    const random =
      filteredQuestions[Math.floor(Math.random() * filteredQuestions.length)]

    if (random) setCurrentQuestion(random)
  }

  const saveFavorite = () => {
    if (!favorites.includes(currentQuestion)) {
      setFavorites([...favorites, currentQuestion])
    }
  }

  const copyQuestion = async () => {
    await navigator.clipboard.writeText(currentQuestion)
    alert("Question copied!")
  }

  return (
    <main
      className={`${darkMode ? "bg-[#09090f] text-white" : "bg-[#f7f4ff] text-zinc-800"} min-h-screen overflow-hidden transition-all duration-500`}
    >
      <div className="absolute inset-0 overflow-hidden -z-10">
        <div className="absolute left-0 top-0 h-72 w-72 rounded-full bg-pink-300/30 blur-3xl animate-pulse" />
        <div className="absolute right-0 top-20 h-96 w-96 rounded-full bg-violet-300/30 blur-3xl animate-pulse" />
        <div className="absolute bottom-0 left-1/3 h-80 w-80 rounded-full bg-sky-300/30 blur-3xl animate-pulse" />
      </div>

      <nav className="sticky top-0 z-50 border-b border-white/10 bg-white/20 backdrop-blur-xl">
        <div className="mx-auto flex max-w-7xl items-center justify-between px-6 py-5">
          <h1 className="bg-gradient-to-r from-pink-500 to-violet-600 bg-clip-text text-3xl font-black text-transparent">
            DeepTalks
          </h1>

          <div className="flex items-center gap-3">
            <button
              onClick={() => setDarkMode(!darkMode)}
              className="rounded-full border border-white/20 bg-white/20 p-3 backdrop-blur-xl transition hover:scale-110"
            >
              <Moon size={18} />
            </button>

            <button className="rounded-full border border-white/20 bg-white/20 p-3 backdrop-blur-xl transition hover:scale-110">
              <Music2 size={18} />
            </button>
          </div>
        </div>
      </nav>

      <section className="mx-auto flex max-w-7xl flex-col items-center justify-between gap-16 px-6 py-24 lg:flex-row">
        <div className="max-w-2xl text-center lg:text-left">
          <div className="mb-6 inline-flex items-center gap-2 rounded-full border border-white/20 bg-white/20 px-5 py-2 text-sm font-semibold backdrop-blur-xl">
            ✨ Modern Conversation Experience
          </div>

          <h1 className="text-6xl font-black leading-tight tracking-tight md:text-7xl">
            Start Better
            <span className="block bg-gradient-to-r from-pink-500 to-violet-600 bg-clip-text text-transparent">
              Conversations
            </span>
          </h1>

          <p className="mt-6 text-lg leading-relaxed opacity-80">
            Temukan pertanyaan seru untuk pasangan, teman, diri sendiri,
            dan anak-anak dalam pengalaman interaktif modern yang aesthetic.
          </p>
        </div>

        <motion.div
          animate={{ y: [0, -12, 0] }}
          transition={{ repeat: Infinity, duration: 4 }}
          className="w-full max-w-sm rounded-[40px] border border-white/20 bg-white/20 p-8 shadow-[0_20px_80px_rgba(0,0,0,0.12)] backdrop-blur-2xl"
        >
          <div className="mb-4 flex items-center justify-between">
            <span className="rounded-full bg-pink-100 px-3 py-1 text-xs font-bold text-pink-600">
              Daily Question
            </span>
            <Sparkles className="text-pink-500" />
          </div>

          <h3 className="text-2xl font-bold leading-relaxed">
            “Apa hal kecil yang paling bikin kamu merasa dicintai?”
          </h3>

          <button
            onClick={generateQuestion}
            className="mt-8 w-full rounded-2xl bg-gradient-to-r from-pink-500 to-violet-600 px-5 py-4 font-semibold text-white transition hover:scale-105"
          >
            Generate Talk
          </button>
        </motion.div>
      </section>

      <section className="mx-auto max-w-7xl px-6 pb-20">
        <div className="mb-12 text-center">
          <h2 className="text-4xl font-black">Choose Your Vibe</h2>
          <p className="mt-3 opacity-70">
            Pick a category and start meaningful conversations.
          </p>
        </div>

        <div className="grid gap-6 md:grid-cols-2 xl:grid-cols-4">
          {categories.map((item) => {
            const Icon = item.icon

            return (
              <motion.button
                whileHover={{ y: -8, scale: 1.02 }}
                key={item.id}
                onClick={() => {
                  setActiveCategory(item.id)
                  setCurrentQuestion(questionData[item.id][0])
                }}
                className={`rounded-[36px] bg-gradient-to-br ${item.gradient} p-[1px] text-left shadow-2xl`}
              >
                <div className="h-full rounded-[35px] border border-white/20 bg-white/40 p-7 backdrop-blur-2xl">
                  <div className="mb-5 flex h-16 w-16 items-center justify-center rounded-3xl bg-white shadow-xl">
                    <Icon size={30} />
                  </div>

                  <h3 className="text-2xl font-black">{item.title}</h3>
                  <p className="mt-3 text-sm opacity-70">{item.desc}</p>
                </div>
              </motion.button>
            )
          })}
        </div>
      </section>

      <section className="mx-auto max-w-5xl px-6 pb-24">
        <div className="rounded-[40px] border border-white/20 bg-white/20 p-8 shadow-[0_20px_80px_rgba(0,0,0,0.12)] backdrop-blur-2xl md:p-12">
          <div className="flex flex-col gap-5 md:flex-row md:items-center md:justify-between">
            <div>
              <span className="rounded-full bg-violet-100 px-4 py-2 text-xs font-bold text-violet-700">
                {categories.find((c) => c.id === activeCategory)?.title}
              </span>

              <AnimatePresence mode="wait">
                <motion.h2
                  key={currentQuestion}
                  initial={{ opacity: 0, y: 20 }}
                  animate={{ opacity: 1, y: 0 }}
                  exit={{ opacity: 0, y: -20 }}
                  transition={{ duration: 0.35 }}
                  className="mt-5 text-3xl font-black leading-relaxed md:text-5xl"
                >
                  “{currentQuestion}”
                </motion.h2>
              </AnimatePresence>
            </div>
          </div>

          <div className="mt-10 flex flex-col gap-4 md:flex-row">
            <button
              onClick={generateQuestion}
              className="flex flex-1 items-center justify-center gap-2 rounded-2xl bg-gradient-to-r from-pink-500 to-violet-600 px-6 py-4 font-semibold text-white shadow-xl transition hover:scale-105"
            >
              <Shuffle size={18} />
              Next Question
            </button>

            <button
              onClick={saveFavorite}
              className="flex items-center justify-center gap-2 rounded-2xl border border-white/20 bg-white/20 px-6 py-4 font-semibold backdrop-blur-xl transition hover:scale-105"
            >
              <Star size={18} />
              Favorite
            </button>

            <button
              onClick={copyQuestion}
              className="flex items-center justify-center gap-2 rounded-2xl border border-white/20 bg-white/20 px-6 py-4 font-semibold backdrop-blur-xl transition hover:scale-105"
            >
              <Copy size={18} />
              Copy
            </button>
          </div>

          <div className="mt-8 flex items-center gap-3 rounded-2xl border border-white/20 bg-white/20 px-5 py-4 backdrop-blur-xl">
            <Search size={18} />
            <input
              value={search}
              onChange={(e) => setSearch(e.target.value)}
              placeholder="Search question..."
              className="w-full bg-transparent outline-none placeholder:text-zinc-400"
            />
          </div>
        </div>
      </section>

      <section className="mx-auto max-w-6xl px-6 pb-28">
        <div className="mb-10 flex items-center gap-3">
          <Smile className="text-pink-500" />
          <h2 className="text-3xl font-black">Favorite Questions</h2>
        </div>

        <div className="grid gap-5 md:grid-cols-2">
          {favorites.length === 0 ? (
            <div className="rounded-3xl border border-dashed border-white/20 bg-white/10 p-8 text-center opacity-70 backdrop-blur-xl">
              No favorite questions yet.
            </div>
          ) : (
            favorites.map((item, index) => (
              <motion.div
                initial={{ opacity: 0, y: 20 }}
                animate={{ opacity: 1, y: 0 }}
                key={index}
                className="rounded-3xl border border-white/20 bg-white/20 p-6 backdrop-blur-xl"
              >
                <p className="text-lg font-medium leading-relaxed">“{item}”</p>
              </motion.div>
            ))
          )}
        </div>
      </section>

      <button
        onClick={generateQuestion}
        className="fixed bottom-6 right-6 rounded-full bg-gradient-to-r from-pink-500 to-violet-600 px-7 py-5 font-bold text-white shadow-[0_10px_50px_rgba(168,85,247,0.45)] transition hover:scale-110"
      >
        ✨ Generate
      </button>
    </main>
  )
}
