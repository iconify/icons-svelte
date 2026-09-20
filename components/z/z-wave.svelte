<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0z4q7cwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0z4q7cwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:z-wave" {...props}></Icon>
