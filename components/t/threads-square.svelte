<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh7tywstp.css';
import '../../css/s/szy8zrbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGngv3Lbdb" class="mh7tywstp"/></defs><use href="#SVGngv3Lbdb"/><path class="szy8zrbsp"/><use href="#SVGngv3Lbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:threads-square" {...props}></Icon>
