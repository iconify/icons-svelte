<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xte0qrb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xte0qrb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wheelchair-fill-round" {...props}></Icon>
