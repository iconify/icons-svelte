<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en0p8sfui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en0p8sfui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wallabag" {...props}></Icon>
