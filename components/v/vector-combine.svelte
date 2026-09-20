<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi2r8foaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2r8foaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-combine" {...props}></Icon>
