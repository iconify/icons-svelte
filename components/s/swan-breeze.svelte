<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocr_1acml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocr_1acml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swan-breeze" {...props}></Icon>
