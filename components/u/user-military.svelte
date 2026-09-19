<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikuckebwq.css';
import '../../css/r/r1o9g9byu.css';
import '../../css/g/gad0czbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ikuckebwq"/><path class="r1o9g9byu"/><path class="gad0czbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-military" {...props}></Icon>
