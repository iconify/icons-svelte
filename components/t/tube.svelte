<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcdsv_bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-9,"top":-2};
const content = `<path class="pcdsv_bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tube" {...props}></Icon>
