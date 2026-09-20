<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5277z8hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5277z8hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rundeck-light" {...props}></Icon>
