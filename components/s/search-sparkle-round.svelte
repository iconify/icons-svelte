<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7q8bf8rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7q8bf8rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:search-sparkle-round" {...props}></Icon>
