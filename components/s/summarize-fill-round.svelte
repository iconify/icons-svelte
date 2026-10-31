<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6u8dutfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6u8dutfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:summarize-fill-round" {...props}></Icon>
