<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9vesdmny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v9vesdmny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:side-panel-close" {...props}></Icon>
