<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aimebubco.css';
import '../../css/o/ova0c4bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aimebubco"/><path class="ova0c4bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-search-bold" {...props}></Icon>
