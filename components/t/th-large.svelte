<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huc0kzbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="huc0kzbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:th-large" {...props}></Icon>
