<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsgvrfbam.css';
import '../../css/h/h_8zds5nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rsgvrfbam"/><path class="h_8zds5nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:telescope-sharp" {...props}></Icon>
