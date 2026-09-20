<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iala6ptcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iala6ptcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:waste-basket" {...props}></Icon>
