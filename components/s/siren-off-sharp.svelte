<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orkh5bv4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orkh5bv4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:siren-off-sharp" {...props}></Icon>
