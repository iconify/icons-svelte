<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz78q1_kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz78q1_kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:xrp" {...props}></Icon>
