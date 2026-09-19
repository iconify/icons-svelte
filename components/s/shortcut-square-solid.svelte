<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssp_4fbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ssp_4fbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shortcut-square-solid" {...props}></Icon>
