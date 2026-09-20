<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo2-bs55y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo2-bs55y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-eye" {...props}></Icon>
