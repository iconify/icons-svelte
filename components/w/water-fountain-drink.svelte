<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr3710ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nr3710ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:water-fountain-drink" {...props}></Icon>
