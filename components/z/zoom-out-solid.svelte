<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4am1db-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r4am1db-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:zoom-out-solid" {...props}></Icon>
