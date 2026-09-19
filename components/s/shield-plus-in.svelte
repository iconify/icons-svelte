<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7qaq_brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7qaq_brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-plus-in" {...props}></Icon>
