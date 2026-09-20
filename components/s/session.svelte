<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvl-vxb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvl-vxb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:session" {...props}></Icon>
