<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl4dxrxeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dl4dxrxeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:trash-bin" {...props}></Icon>
