<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fwfr7jc3g.css';
import '../../css/j/jxwsi6yrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(1 1)" class="bi12bsetm"><path class="fwfr7jc3g"/><circle class="jxwsi6yrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:warning-triangle" {...props}></Icon>
