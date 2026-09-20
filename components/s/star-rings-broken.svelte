<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sm8kzccgq.css';
import '../../css/j/jlj8l_bps.css';
import '../../css/y/yxpmksx3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sm8kzccgq"/><path class="jlj8l_bps"/><path class="yxpmksx3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rings-broken" {...props}></Icon>
