<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj5hfzb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj5hfzb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-fill-round" {...props}></Icon>
