<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg3u83fnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rg3u83fnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:splitthree" {...props}></Icon>
