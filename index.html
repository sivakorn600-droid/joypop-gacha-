<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JOYPOP GACHA - User Edition</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @keyframes slice {
            0% { transform: scale(0.8); opacity: 0; filter: brightness(2); }
            50% { transform: scale(1.1) rotate(3deg); opacity: 1; filter: brightness(1.5); }
            100% { transform: scale(1) rotate(0deg); opacity: 1; filter: brightness(1); }
        }
        .animate-slice { animation: slice 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards; }
    </style>
</head>
<body class="bg-slate-950 text-white font-sans min-h-screen pb-12">

    <!-- Header Navbar -->
    <header class="bg-slate-900 border-b border-slate-800 p-4 sticky top-0 z-40 shadow-md">
        <div class="max-w-md mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-gradient-to-tr from-orange-500 to-amber-400 rounded-xl flex items-center justify-center font-black text-xl shadow-lg">JP</div>
                <div>
                    <h1 class="font-black text-sm tracking-wider text-orange-500">JOYPOP GACHA</h1>
                    <p class="text-[10px] text-slate-400" id="userDisplayStatus">ยังไม่ได้เข้าสู่ระบบ</p>
                </div>
            </div>
            <div id="authHeaderBtn">
                <button onclick="openAuthModal()" class="px-3 py-1.5 bg-orange-600 hover:bg-orange-500 rounded-xl text-xs font-bold shadow-md">เข้าสู่ระบบ / สมัคร</button>
            </div>
        </div>
    </header>

    <main class="max-w-md mx-auto p-4 space-y-4">
        <!-- Wallet & Quick Actions -->
        <div class="bg-slate-900 border border-slate-800 p-4 rounded-2xl shadow-xl flex justify-between items-center">
            <div>
                <p class="text-xs text-slate-400">ยอดเงินคงเหลือ</p>
                <h2 class="text-2xl font-black text-emerald-400" id="walletBalance">0 ฿</h2>
            </div>
            <div class="flex space-x-2">
                <button onclick="openDepositModal()" class="px-3 py-2 bg-emerald-600 hover:bg-emerald-500 rounded-xl text-xs font-bold shadow-lg shadow-emerald-600/30">เติมเงิน</button>
                <button onclick="openWithdrawModal()" class="px-3 py-2 bg-amber-600 hover:bg-amber-500 rounded-xl text-xs font-bold shadow-lg shadow-amber-600/30">ถอนเงิน</button>
                <button onclick="openInventoryModal()" class="px-3 py-2 bg-blue-600 hover:bg-blue-500 rounded-xl text-xs font-bold shadow-lg shadow-blue-600/30 relative">คลัง <span id="inventoryBadge" class="absolute -top-1 -right-1 bg-rose-500 text-[10px] px-1.5 rounded-full hidden">0</span></button>
            </div>
        </div>

        <!-- Live Global Ticker -->
        <div class="bg-slate-900/80 border border-slate-800 px-3 py-2 rounded-xl text-xs flex items-center space-x-2 overflow-hidden shadow-inner">
            <span class="bg-rose-600 text-[10px] px-2 py-0.5 rounded font-bold uppercase tracking-wider shrink-0 animate-pulse">LIVE</span>
            <div class="truncate text-slate-300" id="tickerContent">🔥 🎉 ผู้เล่น user@joypop.com เพิ่งสุ่มได้ <b class="text-amber-400">SP Whitebeard</b> !</div>
        </div>

        <!-- Gacha Machines List -->
        <div class="space-y-4">
            <!-- Machine 1: One Piece -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-4 shadow-xl space-y-3 relative overflow-hidden">
                <div class="absolute top-0 right-0 bg-gradient-to-l from-orange-600 to-transparent px-4 py-1 text-[10px] font-bold text-white rounded-bl-xl">20 ฿ / ครั้ง</div>
                <h3 class="font-black text-base text-orange-400">🏴‍☠️ One Piece Card Pack</h3>
                <p class="text-xs text-slate-400">ลุ้นการ์ดระดับตำนานและเกลือสะสม</p>
                <div class="bg-slate-950/60 p-2.5 rounded-xl text-[11px] text-slate-300 space-y-1">
                    <div class="flex justify-between"><span>⭐ SP Whitebeard</span><span class="text-amber-400 font-bold">1.0%</span></div>
                    <div class="flex justify-between"><span>✨ A Luffy Gear 5</span><span class="text-purple-400 font-bold">3.3%</span></div>
                    <div class="flex justify-between"><span>🧂 C Salt (เกลือ)</span><span class="text-slate-500 font-bold">95.7%</span></div>
                </div>
                <button onclick="rollGacha('onepiece')" class="w-full py-3 bg-gradient-to-r from-orange-600 to-amber-600 hover:from-orange-500 hover:to-amber-500 font-black rounded-xl shadow-lg shadow-orange-600/30 text-sm">สุ่ม 1 ครั้ง (20 ฿)</button>
            </div>

            <!-- Machine 2: Bear Doll -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-4 shadow-xl space-y-3 relative overflow-hidden">
                <div class="absolute top-0 right-0 bg-gradient-to-l from-pink-600 to-transparent px-4 py-1 text-[10px] font-bold text-white rounded-bl-xl">49 ฿ / ครั้ง</div>
                <h3 class="font-black text-base text-pink-400">🧸 Bear Doll Mystery Box</h3>
                <p class="text-xs text-slate-400">กล่องสุ่มตุ๊กตาหมีพรีเมียม ลุ้นแรร์</p>
                <div class="bg-slate-950/60 p-2.5 rounded-xl text-[11px] text-slate-300 space-y-1">
                    <div class="flex justify-between"><span>🧸 SP Teddy Bear</span><span class="text-amber-400 font-bold">10.0%</span></div>
                    <div class="flex justify-between"><span>🧂 C Salt (เกลือ)</span><span class="text-slate-500 font-bold">90.0%</span></div>
                </div>
                <button onclick="rollGacha('bear')" class="w-full py-3 bg-gradient-to-r from-pink-600 to-rose-600 hover:from-pink-500 hover:to-rose-500 font-black rounded-xl shadow-lg shadow-pink-600/30 text-sm">สุ่ม 1 ครั้ง (49 ฿)</button>
            </div>

            <!-- Machine 3: Football Card -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-4 shadow-xl space-y-3 relative overflow-hidden">
                <div class="absolute top-0 right-0 bg-gradient-to-l from-emerald-600 to-transparent px-4 py-1 text-[10px] font-bold text-white rounded-bl-xl">399 ฿ / ครั้ง</div>
                <h3 class="font-black text-base text-emerald-400">⚽ World Class Football Card</h3>
                <p class="text-xs text-slate-400">รวมการ์ดนักเตะลายเซ็นระดับโลก</p>
                <div class="bg-slate-950/60 p-2.5 rounded-xl text-[11px] text-slate-300 space-y-1">
                    <div class="flex justify-between"><span>🌟 SP Paul Scholes Auto</span><span class="text-amber-400 font-bold">1.0%</span></div>
                    <div class="flex justify-between"><span>✨ SA Diogo Jota Auto</span><span class="text-rose-400 font-bold">3.3%</span></div>
                    <div class="flex justify-between"><span>🔥 SS Lionel Messi Auto</span><span class="text-blue-400 font-bold">5.3%</span></div>
                    <div class="flex justify-between"><span>⚡ A Cody Gakpo Auto</span><span class="text-purple-400 font-bold">25.0%</span></div>
                    <div class="flex justify-between"><span>🧂 C Salt (เกลือ)</span><span class="text-slate-500 font-bold">65.4%</span></div>
                </div>
                <button onclick="rollGacha('football')" class="w-full py-3 bg-gradient-to-r from-emerald-600 to-teal-600 hover:from-emerald-500 hover:to-teal-500 font-black rounded-xl shadow-lg shadow-emerald-600/30 text-sm">สุ่ม 1 ครั้ง (399 ฿)</button>
            </div>
        </div>
    </main>

    <!-- Modal: Auth -->
    <div id="authModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 w-full max-w-sm rounded-3xl p-6 space-y-4 shadow-2xl">
            <h2 class="text-lg font-black text-orange-500 text-center">🔐 เข้าสู่ระบบ / สมัครสมาชิก</h2>
            <div class="space-y-3 pt-2">
                <input type="email" id="inputEmail" placeholder="อีเมลของคุณ" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 text-xs focus:outline-none focus:border-orange-500">
                <input type="password" id="inputPassword" placeholder="รหัสผ่าน" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 text-xs focus:outline-none focus:border-orange-500">
                <div class="flex space-x-2 pt-2">
                    <button onclick="handleRegister()" class="w-1/2 py-2.5 bg-blue-600 hover:bg-blue-500 rounded-xl text-xs font-bold shadow-md">สมัครสมาชิก</button>
                    <button onclick="handleLogin()" class="w-1/2 py-2.5 bg-emerald-600 hover:bg-emerald-500 rounded-xl text-xs font-bold shadow-md">เข้าสู่ระบบ</button>
                </div>
            </div>
            <button onclick="closeAuthModal()" class="w-full py-2 bg-slate-800 hover:bg-slate-700 rounded-xl text-xs text-slate-400 font-bold">ปิดหน้าต่าง</button>
        </div>
    </div>

    <!-- Modal: Deposit -->
    <div id="depositModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 w-full max-w-sm rounded-3xl p-6 space-y-4 shadow-2xl">
            <h2 class="text-lg font-black text-emerald-400 text-center">💰 เติมเงินเข้าบัญชี</h2>
            <div class="bg-slate-950 p-3 rounded-2xl text-xs space-y-1 text-slate-300">
                <p><b>โอนผ่าน TrueMoney / ธนาคาร:</b></p>
                <p class="text-amber-400 font-bold text-sm">เบอร์: 063-579-6555</p>
                <p class="text-[10px] text-slate-500">ขั้นต่ำ 100฿ (ธนาคาร) หรือ 10฿ (TrueMoney)</p>
            </div>
            <input type="number" id="depositAmountInput" placeholder="ระบุจำนวนเงินที่ต้องการเติม" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 text-xs focus:outline-none focus:border-emerald-500">
            <button onclick="submitDeposit()" class="w-full py-3 bg-emerald-600 hover:bg-emerald-500 font-black rounded-xl text-xs shadow-lg shadow-emerald-600/30">ยืนยันการเติมเงิน</button>
            <button onclick="closeDepositModal()" class="w-full py-2 bg-slate-800 hover:bg-slate-700 rounded-xl text-xs text-slate-400 font-bold">ปิด</button>
        </div>
    </div>

    <!-- Modal: Withdraw -->
    <div id="withdrawModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 w-full max-w-sm rounded-3xl p-6 space-y-4 shadow-2xl">
            <h2 class="text-lg font-black text-amber-400 text-center">💸 ถอนเงินออกจากระบบ</h2>
            <div class="space-y-3 text-xs">
                <input type="number" id="withdrawAmountInput" placeholder="จำนวนเงินที่ต้องการถอน (ขั้นต่ำ 10 บาท)" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 focus:outline-none focus:border-amber-500">
                <input type="text" id="withdrawAccInput" placeholder="เลขบัญชี หรือ เบอร์ TrueMoney" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 focus:outline-none focus:border-amber-500">
                <input type="text" id="withdrawNameInput" placeholder="ชื่อ-นามสกุล เจ้าของบัญชี" class="w-full px-3 py-2.5 bg-slate-800 rounded-xl border border-slate-700 focus:outline-none focus:border-amber-500">
            </div>
            <button onclick="submitWithdraw()" class="w-full py-3 bg-amber-600 hover:bg-amber-500 font-black rounded-xl text-xs shadow-lg shadow-amber-600/30">ยืนยันการถอนเงิน</button>
            <button onclick="closeWithdrawModal()" class="w-full py-2 bg-slate-800 hover:bg-slate-700 rounded-xl text-xs text-slate-400 font-bold">ปิด</button>
        </div>
    </div>

    <!-- Modal: Inventory -->
    <div id="inventoryModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 w-full max-w-md rounded-3xl p-6 space-y-4 shadow-2xl max-h-[80vh] flex flex-col">
            <div class="flex justify-between items-center">
                <h2 class="text-lg font-black text-blue-400">🎒 คลังไอเทมของฉัน</h2>
                <button onclick="sellAllSalt()" class="px-3 py-1.5 bg-rose-600 hover:bg-rose-500 rounded-xl text-xs font-bold shadow-md">ขายเกลือทั้งหมด (1฿/เกลือ)</button>
            </div>
            <div id="inventoryList" class="space-y-2 overflow-y-auto flex-1 pr-1"></div>
            <button onclick="closeInventoryModal()" class="w-full py-2 bg-slate-800 hover:bg-slate-700 rounded-xl text-xs text-slate-400 font-bold">ปิด</button>
        </div>
    </div>

    <!-- Modal: Roll Result -->
    <div id="resultModal" class="fixed inset-0 bg-black/90 backdrop-blur-md z-50 flex items-center justify-center p-4 hidden">
        <div class="text-center space-y-4 animate-slice">
            <div class="inline-block p-6 bg-slate-900 border-2 border-amber-500/80 rounded-3xl shadow-2xl max-w-xs space-y-3">
                <p class="text-xs text-slate-400 font-bold uppercase tracking-wider">🎉 ยินดีด้วย คุณได้รับ!</p>
                <div id="resultItemName" class="text-xl font-black text-amber-400">SP Whitebeard</div>
                <button onclick="closeResultModal()" class="w-full py-2.5 bg-orange-600 hover:bg-orange-500 rounded-xl font-black text-xs shadow-lg">รับเข้าคลังไอเทม</button>
            </div>
        </div>
    </div>

    <script>
        function getUsersDB() {
            let db = JSON.parse(localStorage.getItem('joypop_users_db'));
            if (!db) {
                db = {};
                localStorage.setItem('joypop_users_db', JSON.stringify(db));
            }
            return db;
        }
        function saveUsersDB(db) {
            localStorage.setItem('joypop_users_db', JSON.stringify(db));
        }

        let currentUserEmail = localStorage.getItem('joypop_logged_user') || null;

        function getCurrentUserData() {
            if (!currentUserEmail) return null;
            const db = getUsersDB();
            return db[currentUserEmail] || null;
        }

        function updateUserData(newData) {
            if (!currentUserEmail) return;
            const db = getUsersDB();
            if (db[currentUserEmail]) {
                db[currentUserEmail] = { ...db[currentUserEmail], ...newData };
                saveUsersDB(db);
                renderUI();
            }
        }

        function openAuthModal() { document.getElementById('authModal').classList.remove('hidden'); }
        function closeAuthModal() { document.getElementById('authModal').classList.add('hidden'); }

        function handleRegister() {
            const email = document.getElementById('inputEmail').value.trim();
            const pass = document.getElementById('inputPassword').value.trim();
            if(!email || !pass) return alert("กรุณากรอกอีเมลและรหัสผ่าน");
            
            const db = getUsersDB();
            if(db[email]) return alert("อีเมลนี้มีผู้ใช้งานแล้ว!");

            // สมัครใหม่เริ่มต้นด้วยยอดเงิน 0 บาท (ไม่มีแจกฟรี)
            db[email] = {
                password: pass,
                wallet: 0,
                inventory: []
            };
            saveUsersDB(db);
            currentUserEmail = email;
            localStorage.setItem('joypop_logged_user', email);
            closeAuthModal();
            alert("สมัครสมาชิกสำเร็จ!");
            renderUI();
        }

        function handleLogin() {
            const email = document.getElementById('inputEmail').value.trim();
            const pass = document.getElementById('inputPassword').value.trim();
            if(!email || !pass) return alert("กรุณากรอกอีเมลและรหัสผ่าน");

            const db = getUsersDB();
            if(!db[email] || db[email].password !== pass) {
                return alert("อีเมลหรือรหัสผ่านไม่ถูกต้อง!");
            }

            currentUserEmail = email;
            localStorage.setItem('joypop_logged_user', email);
            closeAuthModal();
            alert("เข้าสู่ระบบสำเร็จ!");
            renderUI();
        }

        function logout() {
            currentUserEmail = null;
            localStorage.removeItem('joypop_logged_user');
            renderUI();
        }

        function renderUI() {
            const user = getCurrentUserData();
            const headerBtn = document.getElementById('authHeaderBtn');
            const statusText = document.getElementById('userDisplayStatus');
            const walletEl = document.getElementById('walletBalance');
            const badgeEl = document.getElementById('inventoryBadge');

            if(user) {
                statusText.innerText = currentUserEmail;
                walletEl.innerText = (user.wallet || 0).toLocaleString() + " ฿";
                headerBtn.innerHTML = `<button onclick="logout()" class="px-3 py-1.5 bg-rose-600 hover:bg-rose-500 rounded-xl text-xs font-bold shadow-md">ออกจากระบบ</button>`;
                
                const count = user.inventory.length;
                if(count > 0) {
                    badgeEl.innerText = count;
                    badgeEl.classList.remove('hidden');
                } else {
                    badgeEl.classList.add('hidden');
                }
            } else {
                statusText.innerText = "ยังไม่ได้เข้าสู่ระบบ";
                walletEl.innerText = "0 ฿";
                headerBtn.innerHTML = `<button onclick="openAuthModal()" class="px-3 py-1.5 bg-orange-600 hover:bg-orange-500 rounded-xl text-xs font-bold shadow-md">เข้าสู่ระบบ / สมัคร</button>`;
                badgeEl.classList.add('hidden');
            }
        }

        const gachaRates = {
            onepiece: [
                { name: "SP Whitebeard", chance: 1.0 },
                { name: "A Luffy Gear 5", chance: 3.3 },
                { name: "C Salt (เกลือ)", chance: 95.7 }
            ],
            bear: [
                { name: "SP Teddy Bear", chance: 10.0 },
                { name: "C Salt (เกลือ)", chance: 90.0 }
            ],
            football: [
                { name: "SP Paul Scholes Auto", chance: 1.0 },
                { name: "SA Diogo Jota Auto", chance: 3.3 },
                { name: "SS Lionel Messi Auto", chance: 5.3 },
                { name: "A Cody Gakpo Auto", chance: 25.0 },
                { name: "C Salt (เกลือ)", chance: 65.4 }
            ]
        };

        const gachaPrices = { onepiece: 20, bear: 49, football: 399 };
        let pendingItem = null;

        function rollGacha(type) {
            const user = getCurrentUserData();
            if(!user) return alert("กรุณาเข้าสู่ระบบก่อนสุ่มกาชา!");
            const price = gachaPrices[type];
            if(user.wallet < price) return alert("ยอดเงินคงเหลือของคุณไม่พอ กรุณาเติมเงินก่อนครับ!");

            user.wallet -= price;
            const rand = Math.random() * 100;
            let cumulative = 0;
            let pulled = "C Salt (เกลือ)";
            for(let item of gachaRates[type]) {
                cumulative += item.chance;
                if(rand <= cumulative) {
                    pulled = item.name;
                    break;
                }
            }

            pendingItem = pulled;
            updateUserData({ wallet: user.wallet });
            document.getElementById('resultItemName').innerText = pulled;
            document.getElementById('resultModal').classList.remove('hidden');
        }

        function closeResultModal() {
            if(pendingItem) {
                const user = getCurrentUserData();
                if(user) {
                    user.inventory.push(pendingItem);
                    updateUserData({ inventory: user.inventory });
                }
                pendingItem = null;
            }
            document.getElementById('resultModal').classList.add('hidden');
        }

        function openDepositModal() { if(!getCurrentUserData()) return alert("กรุณาเข้าสู่ระบบก่อน!"); document.getElementById('depositModal').classList.remove('hidden'); }
        function closeDepositModal() { document.getElementById('depositModal').classList.add('hidden'); }
        function submitDeposit() {
            const amt = parseInt(document.getElementById('depositAmountInput').value);
            if(!amt || amt < 10) return alert("ยอดเติมขั้นต่ำ 10 บาท");
            const user = getCurrentUserData();
            user.wallet += amt;
            updateUserData({ wallet: user.wallet });
            closeDepositModal();
            alert(`เติมเงินสำเร็จ ${amt.toLocaleString()} บาท!`);
        }

        function openWithdrawModal() { if(!getCurrentUserData()) return alert("กรุณาเข้าสู่ระบบก่อน!"); document.getElementById('withdrawModal').classList.remove('hidden'); }
        function closeWithdrawModal() { document.getElementById('withdrawModal').classList.add('hidden'); }
        function submitWithdraw() {
            const amt = parseInt(document.getElementById('withdrawAmountInput').value);
            const acc = document.getElementById('withdrawAccInput').value.trim();
            const name = document.getElementById('withdrawNameInput').value.trim();
            const user = getCurrentUserData();
            if(!amt || amt < 10) return alert("ถอนเงินขั้นต่ำ 10 บาท");
            if(user.wallet < amt) return alert("ยอดเงินไม่พอถอน");
            if(!acc || !name) return alert("กรุณากรอกข้อมูลบัญชีให้ครบถ้วน");
            user.wallet -= amt;
            updateUserData({ wallet: user.wallet });
            closeWithdrawModal();
            alert(`ทำรายการถอนเงิน ${amt.toLocaleString()} บาท สำเร็จ!`);
        }

        function openInventoryModal() {
            const user = getCurrentUserData();
            if(!user) return alert("กรุณาเข้าสู่ระบบก่อน!");
            const listEl = document.getElementById('inventoryList');
            listEl.innerHTML = "";
            if(user.inventory.length === 0) {
                listEl.innerHTML = `<p class="text-xs text-slate-500 text-center py-6">คลังไอเทมว่างเปล่า</p>`;
            } else {
                user.inventory.forEach((item, idx) => {
                    const isSalt = item.includes("Salt");
                    listEl.innerHTML += `
                        <div class="bg-slate-800 p-2.5 rounded-xl flex justify-between items-center text-xs">
                            <span class="${isSalt ? 'text-slate-400' : 'text-amber-400 font-bold'}">${idx+1}. ${item}</span>
                            <button onclick="sellSingleItem(${idx})" class="px-2.5 py-1 bg-rose-600 hover:bg-rose-500 rounded-lg text-[10px] font-bold">ขาย (${isSalt ? '1฿' : '5฿'})</button>
                        </div>
                    `;
                });
            }
            document.getElementById('inventoryModal').classList.remove('hidden');
        }
        function closeInventoryModal() { document.getElementById('inventoryModal').classList.add('hidden'); }

        function sellSingleItem(idx) {
            const user = getCurrentUserData();
            const item = user.inventory[idx];
            const price = item.includes("Salt") ? 1 : 5;
            user.inventory.splice(idx, 1);
            user.wallet += price;
            updateUserData({ wallet: user.wallet, inventory: user.inventory });
            openInventoryModal();
        }

        function sellAllSalt() {
            const user = getCurrentUserData();
            let count = 0;
            user.inventory = user.inventory.filter(i => { if(i.includes("Salt")) { count++; return false; } return true; });
            if(count === 0) return alert("ไม่มีเกลือในคลัง!");
            user.wallet += count;
            updateUserData({ wallet: user.wallet, inventory: user.inventory });
            openInventoryModal();
            alert(`ขายเกลือทั้งหมด ${count} ชิ้น ได้รับเงิน ${count} บาท!`);
        }

        renderUI();
    </script>
</body>
</html>
