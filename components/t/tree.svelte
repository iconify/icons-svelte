<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-h_l0kyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-h_l0kyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:tree" {...props}></Icon>
