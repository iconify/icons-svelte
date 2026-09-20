<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glo_rsb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glo_rsb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:southwest-airlines" {...props}></Icon>
