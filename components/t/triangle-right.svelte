<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drr888o3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="drr888o3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:triangle-right" {...props}></Icon>
