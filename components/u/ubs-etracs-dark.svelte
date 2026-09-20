<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14lmibdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1411,"height":1557};
const content = `<path class="m14lmibdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ubs-etracs-dark" {...props}></Icon>
