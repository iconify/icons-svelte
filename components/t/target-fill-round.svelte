<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eel_tfbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eel_tfbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:target-fill-round" {...props}></Icon>
