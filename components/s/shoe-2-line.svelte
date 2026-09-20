<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlv3huuyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlv3huuyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shoe-2-line" {...props}></Icon>
