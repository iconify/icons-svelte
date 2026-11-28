<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrme9n-sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jrme9n-sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-check" {...props}></Icon>
