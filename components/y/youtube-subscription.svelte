<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zl3bcns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zl3bcns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:youtube-subscription" {...props}></Icon>
