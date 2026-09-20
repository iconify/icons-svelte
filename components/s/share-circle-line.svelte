<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv81c1eak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv81c1eak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-circle-line" {...props}></Icon>
