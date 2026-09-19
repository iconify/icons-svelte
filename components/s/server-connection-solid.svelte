<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9mz3ibbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9mz3ibbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:server-connection-solid" {...props}></Icon>
