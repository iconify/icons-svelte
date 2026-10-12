<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elt_osbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elt_osbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sheet-filled" {...props}></Icon>
