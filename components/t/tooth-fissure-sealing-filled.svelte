<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqwaw3p0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqwaw3p0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-fissure-sealing-filled" {...props}></Icon>
