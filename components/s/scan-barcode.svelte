<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s64ns0bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s64ns0bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-barcode" {...props}></Icon>
