<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5r654krd.css';
import '../../css/r/rzv19ackg.css';
import '../../css/k/kiwq7bbdz.css';
import '../../css/l/lo37u5bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f5r654krd"/><path class="rzv19ackg"/><path class="kiwq7bbdz"/><path class="lo37u5bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screen-rotate-20" {...props}></Icon>
