<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktv_4zb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ktv_4zb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:trophy" {...props}></Icon>
