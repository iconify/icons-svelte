<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_xu1cb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h_xu1cb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarerecord" {...props}></Icon>
