<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi9uwcchg.css';
import '../../css/k/kz2_3wbrk.css';
import '../../css/k/kn3-ey60h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zi9uwcchg"/><path class="kz2_3wbrk"/><path class="kn3-ey60h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switch-closed-20-bold" {...props}></Icon>
