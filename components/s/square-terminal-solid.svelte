<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxv1a-bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxv1a-bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-terminal-solid" {...props}></Icon>
