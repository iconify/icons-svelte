<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvor7v2hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvor7v2hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tick-circle-filled" {...props}></Icon>
