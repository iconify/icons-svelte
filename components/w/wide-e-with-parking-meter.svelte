<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6yq8fyey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z6yq8fyey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-e-with-parking-meter" {...props}></Icon>
