<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fii5vacoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fii5vacoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:signal-messenger" {...props}></Icon>
