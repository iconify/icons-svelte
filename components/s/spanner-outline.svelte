<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqlamj4tr.css';
import '../../css/c/ctcmn9izu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="uqlamj4tr"/><path class="ctcmn9izu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:spanner-outline" {...props}></Icon>
