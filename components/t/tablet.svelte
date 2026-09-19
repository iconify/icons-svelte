<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwepd2fyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="fwepd2fyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tablet" {...props}></Icon>
