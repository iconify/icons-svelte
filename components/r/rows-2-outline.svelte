<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsg5p00hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsg5p00hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-2-outline" {...props}></Icon>
