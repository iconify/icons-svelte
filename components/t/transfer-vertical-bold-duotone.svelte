<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx4zoabor.css';
import '../../css/p/pm4bswxgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx4zoabor"/><path class="pm4bswxgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transfer-vertical-bold-duotone" {...props}></Icon>
