<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivvx2dbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ivvx2dbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarebookmark" {...props}></Icon>
