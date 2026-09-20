<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx951ac2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xx951ac2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:windsocket" {...props}></Icon>
