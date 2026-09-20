<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl4t4gbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl4t4gbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-bold" {...props}></Icon>
