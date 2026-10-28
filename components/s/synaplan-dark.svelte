<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjo9zj5kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="vjo9zj5kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synaplan-dark" {...props}></Icon>
