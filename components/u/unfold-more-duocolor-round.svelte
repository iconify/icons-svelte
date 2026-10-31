<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3e8c1bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3e8c1bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:unfold-more-duocolor-round" {...props}></Icon>
