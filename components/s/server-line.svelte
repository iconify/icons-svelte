<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9m8-rbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9m8-rbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:server-line" {...props}></Icon>
