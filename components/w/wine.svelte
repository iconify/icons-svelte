<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg168wb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg168wb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:wine" {...props}></Icon>
