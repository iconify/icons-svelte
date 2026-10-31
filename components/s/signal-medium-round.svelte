<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m83pbcczj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m83pbcczj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signal-medium-round" {...props}></Icon>
