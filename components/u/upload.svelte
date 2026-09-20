<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryc6sbc8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryc6sbc8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:upload" {...props}></Icon>
