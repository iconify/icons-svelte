<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ota9wmgua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ota9wmgua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:smiley" {...props}></Icon>
