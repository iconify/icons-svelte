<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl22y94ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl22y94ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stretching-2" {...props}></Icon>
