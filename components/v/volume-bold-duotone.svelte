<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxiyspb3j.css';
import '../../css/u/ub_apgbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wxiyspb3j"/><path class="ub_apgbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-bold-duotone" {...props}></Icon>
