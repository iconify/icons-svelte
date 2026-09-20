<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnbdw3x9y.css';
import '../../css/u/uxsu2sb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnbdw3x9y"/><path class="uxsu2sb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-check-24" {...props}></Icon>
