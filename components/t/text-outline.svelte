<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0szqpn1j.css';
import '../../css/a/a_u_vcn1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0szqpn1j"/><path class="a_u_vcn1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:text-outline" {...props}></Icon>
