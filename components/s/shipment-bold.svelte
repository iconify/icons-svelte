<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4f9tbg5g.css';
import '../../css/v/v8p-pjnia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4f9tbg5g"/><path class="v8p-pjnia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-bold" {...props}></Icon>
