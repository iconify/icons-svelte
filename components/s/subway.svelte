<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbw1h3bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tbw1h3bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:subway" {...props}></Icon>
