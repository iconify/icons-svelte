<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzmt377rd.css';
import '../../css/o/oreh4pgns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lzmt377rd"/><path class="oreh4pgns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-fill-20" {...props}></Icon>
