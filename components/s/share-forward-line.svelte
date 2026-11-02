<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz8plk1ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz8plk1ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-forward-line" {...props}></Icon>
