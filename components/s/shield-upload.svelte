<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqo7z6bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqo7z6bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-upload" {...props}></Icon>
