<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc7sk8bgn.css';
import '../../css/h/hiqojibfd.css';
import '../../css/r/rb9owibwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cc7sk8bgn"/><path class="hiqojibfd"/><path class="rb9owibwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spot-price-48-bold" {...props}></Icon>
