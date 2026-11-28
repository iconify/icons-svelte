<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1xomp0bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1xomp0bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tree-plus" {...props}></Icon>
