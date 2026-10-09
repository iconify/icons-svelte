<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miccwacuq.css';
import '../../css/z/z0q4lw36b.css';
import '../../css/f/f8wc0fbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="miccwacuq"/><path class="z0q4lw36b"/><path class="f8wc0fbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:van-20" {...props}></Icon>
