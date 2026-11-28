<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekkxjwbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekkxjwbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:strikethrough" {...props}></Icon>
