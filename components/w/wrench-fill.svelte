<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcx_-ubej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcx_-ubej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:wrench-fill" {...props}></Icon>
