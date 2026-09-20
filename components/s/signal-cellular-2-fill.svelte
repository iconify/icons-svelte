<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3r2ddc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3r2ddc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-cellular-2-fill" {...props}></Icon>
