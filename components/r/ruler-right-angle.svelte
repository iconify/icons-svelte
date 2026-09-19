<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urq73-b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="urq73-b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ruler-right-angle" {...props}></Icon>
