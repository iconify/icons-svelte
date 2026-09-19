<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfi618g_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="mfi618g_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squaret" {...props}></Icon>
