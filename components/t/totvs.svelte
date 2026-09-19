<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-3oclb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":502,"height":512};
const content = `<path class="e-3oclb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:totvs" {...props}></Icon>
