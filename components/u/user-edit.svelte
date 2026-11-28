<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa9uk5dxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa9uk5dxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-edit" {...props}></Icon>
