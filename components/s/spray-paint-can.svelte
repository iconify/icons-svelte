<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcvuepbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kcvuepbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spray-paint-can" {...props}></Icon>
