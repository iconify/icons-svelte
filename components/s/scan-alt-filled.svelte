<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di17q7f4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di17q7f4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scan-alt-filled" {...props}></Icon>
