<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qllvo_fol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qllvo_fol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-x" {...props}></Icon>
