<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul_1wo81h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ul_1wo81h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:workspace-desk-remix" {...props}></Icon>
