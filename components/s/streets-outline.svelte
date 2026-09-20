<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_x-b-xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nc_x-b-xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-outline" {...props}></Icon>
