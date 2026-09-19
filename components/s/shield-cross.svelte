<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy48pgb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy48pgb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-cross" {...props}></Icon>
