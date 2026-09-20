<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt95cub8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt95cub8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:soundwave-circle" {...props}></Icon>
