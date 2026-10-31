<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgefz0bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgefz0bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:temple-fill-round" {...props}></Icon>
