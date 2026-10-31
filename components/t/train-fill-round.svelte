<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv32cr-lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv32cr-lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:train-fill-round" {...props}></Icon>
