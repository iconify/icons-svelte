<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq8krpblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq8krpblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:silent-fill" {...props}></Icon>
