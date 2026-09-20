<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enwe_hbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enwe_hbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-rounded" {...props}></Icon>
