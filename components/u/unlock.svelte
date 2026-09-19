<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nqo117j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="g1nqo117j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:unlock" {...props}></Icon>
