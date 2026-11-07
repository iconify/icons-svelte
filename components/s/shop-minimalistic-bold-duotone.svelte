<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl7l5cbrw.css';
import '../../css/n/nur9zm4bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl7l5cbrw"/><path class="nur9zm4bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-minimalistic-bold-duotone" {...props}></Icon>
