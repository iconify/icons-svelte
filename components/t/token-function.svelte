<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztp720b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ztp720b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-function" {...props}></Icon>
