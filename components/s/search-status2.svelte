<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzpy-2vtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzpy-2vtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-status2" {...props}></Icon>
