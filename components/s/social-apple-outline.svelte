<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so0eo1u0h.css';
import '../../css/v/vb_z8ebaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="so0eo1u0h"/><path class="vb_z8ebaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-apple-outline" {...props}></Icon>
