<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxc63y5rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxc63y5rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ruby" {...props}></Icon>
