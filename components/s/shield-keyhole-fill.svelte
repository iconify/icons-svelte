<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyjuc4bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyjuc4bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-keyhole-fill" {...props}></Icon>
