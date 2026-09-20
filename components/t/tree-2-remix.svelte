<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsih90_mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gsih90_mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tree-2-remix" {...props}></Icon>
