<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w27-8wbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w27-8wbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:torch-filled" {...props}></Icon>
