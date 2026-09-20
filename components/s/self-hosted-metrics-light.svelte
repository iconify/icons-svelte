<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu3kveshj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu3kveshj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-metrics-light" {...props}></Icon>
