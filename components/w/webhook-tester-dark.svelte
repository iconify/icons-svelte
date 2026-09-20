<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwv2rb7dk.css';
import '../../css/e/ejz03ub5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwv2rb7dk"/><path class="ejz03ub5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webhook-tester-dark" {...props}></Icon>
