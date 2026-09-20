<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szbk04d_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="szbk04d_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrob-light" {...props}></Icon>
