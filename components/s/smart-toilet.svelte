<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6_zp-bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6_zp-bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-toilet" {...props}></Icon>
