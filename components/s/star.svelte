<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_c1hybew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_c1hybew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star" {...props}></Icon>
