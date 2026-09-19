<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8utzgnxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8utzgnxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:table" {...props}></Icon>
