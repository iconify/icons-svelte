<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e27oc0i3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e27oc0i3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vip-diamond-fill" {...props}></Icon>
