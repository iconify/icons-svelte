<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruyml-dmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruyml-dmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:workspace-desk-remix" {...props}></Icon>
