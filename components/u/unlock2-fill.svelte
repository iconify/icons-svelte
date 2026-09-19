<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djo92_bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="djo92_bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:unlock2-fill" {...props}></Icon>
