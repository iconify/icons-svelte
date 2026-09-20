<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s87_q_bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s87_q_bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unverified-16" {...props}></Icon>
