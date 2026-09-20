<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klb17b-9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klb17b-9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tea" {...props}></Icon>
