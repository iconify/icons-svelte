<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3gq70bqw.css';
import '../../css/v/v3xbnm0nn.css';
import '../../css/w/wdvky-a2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="l3gq70bqw"/><path class="v3xbnm0nn"/><path class="wdvky-a2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:sort" {...props}></Icon>
