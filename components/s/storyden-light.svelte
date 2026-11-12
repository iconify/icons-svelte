<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu_y8ebyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu_y8ebyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden-light" {...props}></Icon>
