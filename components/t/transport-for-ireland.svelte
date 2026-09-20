<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysyqdbbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysyqdbbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:transport-for-ireland" {...props}></Icon>
