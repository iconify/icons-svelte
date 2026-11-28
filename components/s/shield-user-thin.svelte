<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap1_i8bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ap1_i8bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-user-thin" {...props}></Icon>
