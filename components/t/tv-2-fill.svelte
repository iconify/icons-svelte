<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap9j0fbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ap9j0fbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-2-fill" {...props}></Icon>
