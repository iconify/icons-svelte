<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjny1bchv.css';
import '../../css/x/xpq7hmt-u.css';
import '../../css/x/xyw2m9brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fjny1bchv"/><path class="xpq7hmt-u"/><path class="xyw2m9brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-size-48-bold" {...props}></Icon>
