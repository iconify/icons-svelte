<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwuqmnbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwuqmnbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-down-light" {...props}></Icon>
