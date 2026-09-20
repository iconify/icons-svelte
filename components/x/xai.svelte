<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f25tpeb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f25tpeb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xai" {...props}></Icon>
