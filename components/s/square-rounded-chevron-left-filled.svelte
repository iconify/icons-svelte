<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpti6ab8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpti6ab8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevron-left-filled" {...props}></Icon>
