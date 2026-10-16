<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlx-j4b2l.css';
import '../../css/i/i1jiqq9ax.css';
import '../../css/q/qrdc0-ekd.css';
import '../../css/x/xfroabbqq.css';
import '../../css/o/oiztm8pon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qlx-j4b2l"/><path class="i1jiqq9ax"/><path class="qrdc0-ekd"/><path class="xfroabbqq"/><path class="oiztm8pon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:timeline-20-bold" {...props}></Icon>
