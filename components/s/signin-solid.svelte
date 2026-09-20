<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv77d5bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bv77d5bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:signin-solid" {...props}></Icon>
