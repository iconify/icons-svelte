<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_jz1gb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":2048};
const content = `<path class="v_jz1gb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sheep" {...props}></Icon>
