<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb8srpzjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sb8srpzjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sigma" {...props}></Icon>
