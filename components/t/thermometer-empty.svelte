<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt8qg7b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1792};
const content = `<path class="jt8qg7b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thermometer-empty" {...props}></Icon>
