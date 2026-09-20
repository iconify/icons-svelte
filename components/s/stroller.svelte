<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on6e2sbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="on6e2sbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:stroller" {...props}></Icon>
