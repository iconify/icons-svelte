<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndcw-pbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndcw-pbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-fill-round" {...props}></Icon>
