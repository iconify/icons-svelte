<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsrwsobyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsrwsobyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-hexagon-filled" {...props}></Icon>
