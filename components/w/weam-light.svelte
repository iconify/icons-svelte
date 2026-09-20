<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuz27cc_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuz27cc_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weam-light" {...props}></Icon>
