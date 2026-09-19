<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ue5bb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v4ue5bb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-circle-fill-12" {...props}></Icon>
