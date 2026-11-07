<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixkakeb2a.css';
import '../../css/i/ia9jguu5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixkakeb2a"/><path clip-rule="evenodd" class="ia9jguu5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-trash-bold" {...props}></Icon>
