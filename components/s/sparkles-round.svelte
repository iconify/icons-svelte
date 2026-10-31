<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9r6xxbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9r6xxbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkles-round" {...props}></Icon>
