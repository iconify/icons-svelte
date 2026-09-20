<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzap-88ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzap-88ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-barcode-sharp" {...props}></Icon>
