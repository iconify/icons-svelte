<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfygh5brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfygh5brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vim" {...props}></Icon>
