<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bao23p41t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bao23p41t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-lock-fill" {...props}></Icon>
