<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g88e3l7_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g88e3l7_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:table-branded-row" {...props}></Icon>
