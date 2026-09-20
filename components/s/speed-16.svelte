<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vptlwka5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vptlwka5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:speed-16" {...props}></Icon>
