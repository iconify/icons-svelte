<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1u-c7bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="u1u-c7bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:temperature-quarter" {...props}></Icon>
