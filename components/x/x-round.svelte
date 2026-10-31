<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln93r60js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln93r60js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:x-round" {...props}></Icon>
