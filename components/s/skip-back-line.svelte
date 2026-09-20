<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s842tlblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s842tlblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-back-line" {...props}></Icon>
