<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29abmbpa.css';
import '../../css/q/qa1c6nb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h29abmbpa"/><path class="qa1c6nb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-2-line" {...props}></Icon>
