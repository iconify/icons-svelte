<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7l0bboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cy7l0bboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:star-slash-thin" {...props}></Icon>
