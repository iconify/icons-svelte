<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8r31rbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8r31rbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ticket-round" {...props}></Icon>
