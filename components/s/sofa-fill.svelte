<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt1rxab8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt1rxab8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sofa-fill" {...props}></Icon>
