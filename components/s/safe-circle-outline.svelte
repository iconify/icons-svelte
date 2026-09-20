<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syir6n91y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syir6n91y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-circle-outline" {...props}></Icon>
