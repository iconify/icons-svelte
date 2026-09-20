<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpsb4mp_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bpsb4mp_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:yin-yang-on-square" {...props}></Icon>
