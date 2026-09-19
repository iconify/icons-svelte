<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev061dfmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ev061dfmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:stumbleupon" {...props}></Icon>
