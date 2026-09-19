<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6902sabf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r6902sabf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:save" {...props}></Icon>
