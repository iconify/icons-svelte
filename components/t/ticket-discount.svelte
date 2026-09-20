<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odnm3i3de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odnm3i3de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-discount" {...props}></Icon>
