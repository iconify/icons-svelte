<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3oz6trwf.css';
import '../../css/d/dmz5tfbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3oz6trwf"/><path class="dmz5tfbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:syringe-bold" {...props}></Icon>
