<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jve-jy1ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jve-jy1ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tricentis" {...props}></Icon>
