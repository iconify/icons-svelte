<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkqk3tprm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkqk3tprm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-check-outline" {...props}></Icon>
