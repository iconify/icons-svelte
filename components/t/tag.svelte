<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-7g6-bii.css';
import '../../css/a/a7xkecbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="b-7g6-bii"/><path class="a7xkecbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:tag" {...props}></Icon>
