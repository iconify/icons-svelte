<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqoa_wf6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqoa_wf6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:saving-bull-market" {...props}></Icon>
