<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anupi1uga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anupi1uga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-broken" {...props}></Icon>
