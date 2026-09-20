<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhw8w_bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uhw8w_bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:up-triangle" {...props}></Icon>
