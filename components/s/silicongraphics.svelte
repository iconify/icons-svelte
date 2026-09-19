<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8khk_4lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":506,"height":512};
const content = `<path class="f8khk_4lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:silicongraphics" {...props}></Icon>
