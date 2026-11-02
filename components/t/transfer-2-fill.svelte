<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxb9q8b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxb9q8b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-2-fill" {...props}></Icon>
