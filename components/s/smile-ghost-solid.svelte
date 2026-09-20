<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prstx4uvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prstx4uvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:smile-ghost-solid" {...props}></Icon>
