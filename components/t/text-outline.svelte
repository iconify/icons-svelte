<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuds1jrnr.css';
import '../../css/a/a_u_vcn1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kuds1jrnr"/><path class="a_u_vcn1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:text-outline" {...props}></Icon>
