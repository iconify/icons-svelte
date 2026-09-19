<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai2ywhbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai2ywhbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:spotpear-cube" {...props}></Icon>
