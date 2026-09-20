<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sluqg8b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sluqg8b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:safe" {...props}></Icon>
