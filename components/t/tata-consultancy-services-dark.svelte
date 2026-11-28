<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg_p-hb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1786,"height":428,"left":107,"top":786};
const content = `<path class="wg_p-hb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tata-consultancy-services-dark" {...props}></Icon>
