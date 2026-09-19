<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl69w69-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rl69w69-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:vimeo-v" {...props}></Icon>
