<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7q0ht_hy.css';
import '../../css/d/dvn4mnkrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q7q0ht_hy"/><path class="dvn4mnkrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:streamlit-wordmark" {...props}></Icon>
