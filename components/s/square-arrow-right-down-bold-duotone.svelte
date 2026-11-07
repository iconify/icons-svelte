<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atpjn6hvy.css';
import '../../css/a/at2vc6bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atpjn6hvy"/><path class="at2vc6bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-down-bold-duotone" {...props}></Icon>
