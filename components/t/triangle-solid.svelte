<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8bhgdc_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n8bhgdc_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:triangle-solid" {...props}></Icon>
