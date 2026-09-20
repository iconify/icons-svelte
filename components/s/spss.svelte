<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmuxkt6oo.css';
import '../../css/e/ervpfvb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cmuxkt6oo"/><path class="ervpfvb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spss" {...props}></Icon>
