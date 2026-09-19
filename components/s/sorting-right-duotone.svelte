<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-3-4ac2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3-4ac2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-right-duotone" {...props}></Icon>
