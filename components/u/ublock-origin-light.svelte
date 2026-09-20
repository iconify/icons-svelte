<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxuj48blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxuj48blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ublock-origin-light" {...props}></Icon>
