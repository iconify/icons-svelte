<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v763qvp_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v763qvp_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:sketch" {...props}></Icon>
