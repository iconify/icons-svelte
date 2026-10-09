<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp0mn-ncp.css';
import '../../css/g/gxglj2bzq.css';
import '../../css/d/dq8fo2c6v.css';
import '../../css/e/ey9tmrrek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bp0mn-ncp"/><path class="gxglj2bzq"/><path class="dq8fo2c6v"/><path class="ey9tmrrek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:satellite-20-bold" {...props}></Icon>
