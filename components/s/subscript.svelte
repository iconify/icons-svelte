<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7p0qouo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hn7p0qouo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:subscript" {...props}></Icon>
