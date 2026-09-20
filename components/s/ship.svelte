<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7841yalq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7841yalq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ship" {...props}></Icon>
