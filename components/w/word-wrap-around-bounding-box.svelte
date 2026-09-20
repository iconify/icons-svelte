<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqt6r9oga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lqt6r9oga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:word-wrap-around-bounding-box" {...props}></Icon>
