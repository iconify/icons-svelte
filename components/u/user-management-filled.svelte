<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs_b2rwwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs_b2rwwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-management-filled" {...props}></Icon>
