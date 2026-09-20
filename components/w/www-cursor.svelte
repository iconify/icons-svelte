<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9z2gwbot.css';
import '../../css/c/czgjawueq.css';
import '../../css/g/gbe5vwbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9z2gwbot"/><path class="czgjawueq"/><path clip-rule="evenodd" class="gbe5vwbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:www-cursor" {...props}></Icon>
