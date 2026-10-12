<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phndxwbwk.css';
import '../../css/t/t2rkmiqgs.css';
import '../../css/r/rbnt2jbrg.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="phndxwbwk"/><path class="t2rkmiqgs"/><path class="rbnt2jbrg"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-check-20-bold" {...props}></Icon>
