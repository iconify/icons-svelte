<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aick66v3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aick66v3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tally-five" {...props}></Icon>
