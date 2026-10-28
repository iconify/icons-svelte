<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_gly58ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="d_gly58ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synaplan-light" {...props}></Icon>
