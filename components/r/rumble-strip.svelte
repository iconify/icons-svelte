<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l35ux5oxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l35ux5oxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:rumble-strip" {...props}></Icon>
