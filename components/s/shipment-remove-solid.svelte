<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc__70bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oc__70bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shipment-remove-solid" {...props}></Icon>
