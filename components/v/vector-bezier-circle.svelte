<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap95lub3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap95lub3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vector-bezier-circle" {...props}></Icon>
