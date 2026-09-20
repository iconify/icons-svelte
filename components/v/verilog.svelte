<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scpdkmq3k.css';
import '../../css/y/yst55_15i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="scpdkmq3k"/><path class="yst55_15i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:verilog" {...props}></Icon>
