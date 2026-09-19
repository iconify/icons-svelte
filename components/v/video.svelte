<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_np0rlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="mj_np0rlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:video" {...props}></Icon>
