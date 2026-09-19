<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr8tbrt_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr8tbrt_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:step-forward" {...props}></Icon>
