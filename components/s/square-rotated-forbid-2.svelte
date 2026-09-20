<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owd89xb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owd89xb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rotated-forbid-2" {...props}></Icon>
