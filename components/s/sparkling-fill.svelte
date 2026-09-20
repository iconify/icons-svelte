<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlc0wtbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlc0wtbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sparkling-fill" {...props}></Icon>
