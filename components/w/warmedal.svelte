<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwto_gbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="iwto_gbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:warmedal" {...props}></Icon>
