<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfndc6b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hfndc6b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squares" {...props}></Icon>
