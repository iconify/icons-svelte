<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgnr07vat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mgnr07vat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-square-bold" {...props}></Icon>
