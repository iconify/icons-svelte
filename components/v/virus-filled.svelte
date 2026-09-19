<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-b-vz0ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b-vz0ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:virus-filled" {...props}></Icon>
