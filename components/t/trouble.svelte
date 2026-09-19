<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf8q4cbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="jf8q4cbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:trouble" {...props}></Icon>
