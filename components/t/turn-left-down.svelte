<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrk-82bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrk-82bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:turn-left-down" {...props}></Icon>
