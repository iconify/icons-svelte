<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npm2oqxob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npm2oqxob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subarr-light" {...props}></Icon>
