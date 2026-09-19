<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf7bh81uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bf7bh81uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vsphere-wordmark" {...props}></Icon>
