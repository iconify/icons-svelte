<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxjc86b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxjc86b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unlimited" {...props}></Icon>
