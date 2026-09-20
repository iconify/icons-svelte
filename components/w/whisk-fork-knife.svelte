<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sotyw2bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sotyw2bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:whisk-fork-knife" {...props}></Icon>
