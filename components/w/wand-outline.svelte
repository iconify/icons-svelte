<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl821gjyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yl821gjyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wand-outline" {...props}></Icon>
