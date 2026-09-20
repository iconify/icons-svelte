<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2zuq-bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2zuq-bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-up" {...props}></Icon>
