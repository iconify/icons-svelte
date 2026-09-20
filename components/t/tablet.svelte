<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue4_x5bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue4_x5bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tablet" {...props}></Icon>
