<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9j0h5ort.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9j0h5ort"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:voice-scan" {...props}></Icon>
