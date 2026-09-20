<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u_tug-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1411,"height":1557};
const content = `<path class="m8u_tug-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ubs-etracs-light" {...props}></Icon>
