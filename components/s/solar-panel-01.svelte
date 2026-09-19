<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va9eu4b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va9eu4b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:solar-panel-01" {...props}></Icon>
