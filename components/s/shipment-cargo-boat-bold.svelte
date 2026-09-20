<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcmznibzp.css';
import '../../css/o/of6h3jbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcmznibzp"/><path class="of6h3jbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-cargo-boat-bold" {...props}></Icon>
