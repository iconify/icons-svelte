<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr8x_qhrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr8x_qhrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vince" {...props}></Icon>
