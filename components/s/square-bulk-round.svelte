<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqn404ock.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqn404ock"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-bulk-round" {...props}></Icon>
