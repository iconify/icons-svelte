<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zu__i3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zu__i3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:street-road-1-filled" {...props}></Icon>
