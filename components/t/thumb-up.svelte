<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo-lb0b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="qo-lb0b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:thumb-up" {...props}></Icon>
