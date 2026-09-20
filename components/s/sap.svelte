<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxr707b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxr707b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sap" {...props}></Icon>
