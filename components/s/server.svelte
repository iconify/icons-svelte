<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9n_1vyxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9n_1vyxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:server" {...props}></Icon>
