<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx6hg60hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nx6hg60hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:scuba-diving" {...props}></Icon>
