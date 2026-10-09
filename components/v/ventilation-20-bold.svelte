<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coivkzecr.css';
import '../../css/p/p8-ltwbll.css';
import '../../css/y/yzgpzhz2h.css';
import '../../css/e/en2-8kltz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="p8-ltwbll"/><path class="yzgpzhz2h"/><path class="en2-8kltz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ventilation-20-bold" {...props}></Icon>
