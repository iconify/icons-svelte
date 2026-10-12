<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw1k1qbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw1k1qbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squirrel-filled" {...props}></Icon>
