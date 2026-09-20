<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_l8lhbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_l8lhbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:starburst-outline" {...props}></Icon>
