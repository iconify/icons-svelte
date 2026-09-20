<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7c1f8bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7c1f8bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:siren-sharp" {...props}></Icon>
