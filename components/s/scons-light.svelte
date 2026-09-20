<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9g4-upkk.css';
import '../../css/j/j4n-avbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9g4-upkk"/><path class="j4n-avbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:scons-light" {...props}></Icon>
