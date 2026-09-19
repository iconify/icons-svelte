<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk-s2w2fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tk-s2w2fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tumblr" {...props}></Icon>
