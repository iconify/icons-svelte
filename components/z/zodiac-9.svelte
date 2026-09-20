<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3nddsbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u3nddsbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-9" {...props}></Icon>
