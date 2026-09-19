<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9dxnnbae.css';
import '../../css/s/spzrtb9gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9dxnnbae"/><path class="spzrtb9gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shuffle-sharp" {...props}></Icon>
