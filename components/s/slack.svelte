<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds0-job7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds0-job7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:slack" {...props}></Icon>
