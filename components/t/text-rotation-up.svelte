<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smw7apbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="smw7apbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-rotation-up" {...props}></Icon>
