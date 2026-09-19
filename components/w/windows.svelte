<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xru2yjmmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="xru2yjmmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:windows" {...props}></Icon>
