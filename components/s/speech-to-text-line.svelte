<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t96m9ac6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t96m9ac6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speech-to-text-line" {...props}></Icon>
