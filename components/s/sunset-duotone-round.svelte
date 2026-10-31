<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c180_r4qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c180_r4qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sunset-duotone-round" {...props}></Icon>
