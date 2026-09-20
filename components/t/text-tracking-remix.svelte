<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr1fmvf1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wr1fmvf1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-tracking-remix" {...props}></Icon>
