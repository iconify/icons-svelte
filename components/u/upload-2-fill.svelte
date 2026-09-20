<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luisst6gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luisst6gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:upload-2-fill" {...props}></Icon>
