<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilrh5njzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilrh5njzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:scan-barcode-sharp" {...props}></Icon>
