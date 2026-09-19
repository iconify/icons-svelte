<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddr35hjpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddr35hjpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:temperature-filled" {...props}></Icon>
