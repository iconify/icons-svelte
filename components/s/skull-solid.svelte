<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_ghebcwv.css';
import '../../css/f/f7hsq-06y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p_ghebcwv"/><path clip-rule="evenodd" class="f7hsq-06y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:skull-solid" {...props}></Icon>
