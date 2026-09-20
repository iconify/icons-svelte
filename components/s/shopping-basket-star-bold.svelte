<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg7hhucff.css';
import '../../css/i/i57-i0ixs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg7hhucff"/><path class="i57-i0ixs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-basket-star-bold" {...props}></Icon>
