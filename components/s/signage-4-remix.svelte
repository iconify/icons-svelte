<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di142kb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="di142kb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signage-4-remix" {...props}></Icon>
