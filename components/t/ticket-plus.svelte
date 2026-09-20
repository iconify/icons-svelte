<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe8bcf4ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe8bcf4ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ticket-plus" {...props}></Icon>
