<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnbn3ib9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="wnbn3ib9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synaplan" {...props}></Icon>
