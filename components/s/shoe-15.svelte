<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd11hok7e.css';
import '../../css/r/rw7vibdxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dd11hok7e"/><path class="rw7vibdxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shoe-15" {...props}></Icon>
