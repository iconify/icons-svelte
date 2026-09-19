<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8tdxbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="jg8tdxbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:wink" {...props}></Icon>
