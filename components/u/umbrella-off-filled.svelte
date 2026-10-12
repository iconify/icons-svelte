<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvdzlxb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvdzlxb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:umbrella-off-filled" {...props}></Icon>
