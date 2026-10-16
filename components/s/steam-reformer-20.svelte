<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c38ur7vib.css';
import '../../css/f/fwwetn73i.css';
import '../../css/v/vu0y6dd0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c38ur7vib"/><path class="fwwetn73i"/><path class="vu0y6dd0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steam-reformer-20" {...props}></Icon>
