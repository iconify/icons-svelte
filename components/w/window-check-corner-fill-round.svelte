<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icd4edb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icd4edb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-check-corner-fill-round" {...props}></Icon>
