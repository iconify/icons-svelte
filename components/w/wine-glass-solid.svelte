<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi0e_db3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oi0e_db3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wine-glass-solid" {...props}></Icon>
