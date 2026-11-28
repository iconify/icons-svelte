<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kugr_vbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kugr_vbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:volume-plus" {...props}></Icon>
