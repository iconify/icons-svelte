<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag8vmcb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8vmcb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:toggle-left-fill-round" {...props}></Icon>
