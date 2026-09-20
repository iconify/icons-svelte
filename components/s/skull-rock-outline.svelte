<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxw6x99ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rxw6x99ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skull-rock-outline" {...props}></Icon>
