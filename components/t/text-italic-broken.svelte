<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq5ja2bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq5ja2bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-broken" {...props}></Icon>
