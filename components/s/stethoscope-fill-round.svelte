<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhjf6rbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhjf6rbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stethoscope-fill-round" {...props}></Icon>
