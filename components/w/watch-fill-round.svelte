<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixp0i4b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixp0i4b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:watch-fill-round" {...props}></Icon>
