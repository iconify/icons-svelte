<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p--sl88pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p--sl88pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sign-in-alt" {...props}></Icon>
