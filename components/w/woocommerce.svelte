<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiub_ndwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiub_ndwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:woocommerce" {...props}></Icon>
