<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rydskfbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rydskfbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sofa3" {...props}></Icon>
