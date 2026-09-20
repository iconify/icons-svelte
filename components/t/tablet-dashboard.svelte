<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bubjxie-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bubjxie-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tablet-dashboard" {...props}></Icon>
