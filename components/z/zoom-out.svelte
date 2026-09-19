<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4upji2kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4upji2kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:zoom-out" {...props}></Icon>
