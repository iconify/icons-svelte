<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgvk4i-fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgvk4i-fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-multiple-group-remix" {...props}></Icon>
