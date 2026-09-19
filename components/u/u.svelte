<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg71s5b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bg71s5b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:u" {...props}></Icon>
