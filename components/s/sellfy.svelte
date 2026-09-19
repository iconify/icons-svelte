<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cps6dobbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cps6dobbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sellfy" {...props}></Icon>
