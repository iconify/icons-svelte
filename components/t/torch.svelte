<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_bpy3prm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_bpy3prm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:torch" {...props}></Icon>
