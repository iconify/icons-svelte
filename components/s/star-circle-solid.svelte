<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7k6-lm3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a7k6-lm3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:star-circle-solid" {...props}></Icon>
