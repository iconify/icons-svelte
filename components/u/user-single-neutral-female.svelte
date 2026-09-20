<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzi8x3byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzi8x3byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-single-neutral-female" {...props}></Icon>
