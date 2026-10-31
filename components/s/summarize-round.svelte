<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv7e3w10i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7e3w10i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:summarize-round" {...props}></Icon>
