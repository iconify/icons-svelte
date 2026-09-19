<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5c6ykbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r5c6ykbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zodiaclibra" {...props}></Icon>
