<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sro41zbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sro41zbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shovel-rake" {...props}></Icon>
