<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6fd5rkcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6fd5rkcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:vimeo" {...props}></Icon>
