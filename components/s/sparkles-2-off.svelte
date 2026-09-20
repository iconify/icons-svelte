<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csn_ierpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csn_ierpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sparkles-2-off" {...props}></Icon>
