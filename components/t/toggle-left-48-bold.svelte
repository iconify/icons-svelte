<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcjxo_wu.css';
import '../../css/c/c_4ww1bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dxcjxo_wu"/><path class="c_4ww1bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-left-48-bold" {...props}></Icon>
