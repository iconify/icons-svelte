<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m07t8yn0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m07t8yn0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:seaplane" {...props}></Icon>
