<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_zk3-m4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k_zk3-m4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vyper" {...props}></Icon>
