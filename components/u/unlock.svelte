<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkqk8irly.css';
import '../../css/c/cypjnfb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gkqk8irly"/><path class="cypjnfb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:unlock" {...props}></Icon>
