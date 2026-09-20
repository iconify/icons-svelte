<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3o_rcben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3o_rcben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:thumbs-ok" {...props}></Icon>
