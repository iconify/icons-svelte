<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4dlu5vmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dlu5vmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:voice-square" {...props}></Icon>
