<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8w7s9gyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a8w7s9gyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:saxophone-filled" {...props}></Icon>
