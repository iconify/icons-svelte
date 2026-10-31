<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mulepgbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mulepgbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:split-duocolor-round" {...props}></Icon>
