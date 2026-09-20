<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l66csu07v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l66csu07v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-minus" {...props}></Icon>
