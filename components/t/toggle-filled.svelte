<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orjn0-yiw.css';
import '../../css/j/jir5wfbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="orjn0-yiw"/><path class="jir5wfbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:toggle-filled" {...props}></Icon>
