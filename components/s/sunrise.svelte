<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb_t3abty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hb_t3abty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sunrise" {...props}></Icon>
