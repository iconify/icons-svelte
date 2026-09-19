<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlgp0hbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jlgp0hbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:vimeo-square" {...props}></Icon>
