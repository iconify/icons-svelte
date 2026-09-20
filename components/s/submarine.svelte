<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6f9-1jwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6f9-1jwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:submarine" {...props}></Icon>
