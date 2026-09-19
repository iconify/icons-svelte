<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fguy_qbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fguy_qbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarepause" {...props}></Icon>
