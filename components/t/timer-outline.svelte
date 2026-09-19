<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap74bobrt.css';
import '../../css/s/srw4vobtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap74bobrt"/><path class="srw4vobtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:timer-outline" {...props}></Icon>
