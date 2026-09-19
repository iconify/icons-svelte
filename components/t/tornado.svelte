<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn_cz7bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tn_cz7bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tornado" {...props}></Icon>
