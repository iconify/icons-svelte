<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7rp-2o6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="l7rp-2o6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tenge-sign" {...props}></Icon>
