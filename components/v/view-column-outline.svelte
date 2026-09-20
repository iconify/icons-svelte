<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft8ybjbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ft8ybjbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:view-column-outline" {...props}></Icon>
