<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q23-jybty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q23-jybty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:thumb-down-light" {...props}></Icon>
