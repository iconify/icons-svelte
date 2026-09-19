<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3tpr6m5p.css';
import '../../css/c/c4dnf880p.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 p3tpr6m5p"/><path class="c4dnf880p clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:thumbs-down-solid" {...props}></Icon>
