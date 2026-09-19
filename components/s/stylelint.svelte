<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-sr4yt-t.css';
import '../../css/l/l3cxynbly.css';
import '../../css/a/asc15gb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":525,"height":512};
const content = `<path class="z-sr4yt-t"/><path class="l3cxynbly"/><path class="asc15gb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stylelint" {...props}></Icon>
