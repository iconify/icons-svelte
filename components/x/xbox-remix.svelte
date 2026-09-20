<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wswvxk1sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wswvxk1sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:xbox-remix" {...props}></Icon>
