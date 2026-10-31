<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwbr22b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwbr22b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-help-round" {...props}></Icon>
