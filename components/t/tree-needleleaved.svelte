<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gky2je_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gky2je_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tree-needleleaved" {...props}></Icon>
