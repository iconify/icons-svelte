<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lra8npb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lra8npb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-20-solid" {...props}></Icon>
