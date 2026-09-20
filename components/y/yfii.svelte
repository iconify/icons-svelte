<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vni3thtmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vni3thtmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:yfii" {...props}></Icon>
