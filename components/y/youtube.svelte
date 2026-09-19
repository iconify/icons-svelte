<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0d0qdihh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="m0d0qdihh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:youtube" {...props}></Icon>
