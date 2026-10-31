<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8yi0vlry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8yi0vlry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signal-medium-fill-round" {...props}></Icon>
