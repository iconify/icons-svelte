<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmetgsbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bmetgsbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-vimeo" {...props}></Icon>
