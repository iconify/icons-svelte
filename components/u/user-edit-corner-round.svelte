<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmq596bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmq596bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-edit-corner-round" {...props}></Icon>
