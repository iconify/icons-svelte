<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgsp_6sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgsp_6sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-search" {...props}></Icon>
