<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsi_ej0qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsi_ej0qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round-x" {...props}></Icon>
