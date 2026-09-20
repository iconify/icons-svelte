<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnw2i6g0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnw2i6g0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sofa-sharp" {...props}></Icon>
