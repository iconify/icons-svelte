<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0l7hg_sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0l7hg_sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:typhoon-fill" {...props}></Icon>
