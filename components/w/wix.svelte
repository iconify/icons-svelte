<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvhnsbcah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvhnsbcah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:wix" {...props}></Icon>
