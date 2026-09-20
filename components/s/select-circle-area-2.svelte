<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-7ny1epj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-7ny1epj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:select-circle-area-2" {...props}></Icon>
