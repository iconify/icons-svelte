<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_-jczb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h_-jczb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:zodiac-5-flat" {...props}></Icon>
