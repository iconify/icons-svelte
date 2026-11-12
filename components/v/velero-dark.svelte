<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-bww5bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-bww5bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:velero-dark" {...props}></Icon>
