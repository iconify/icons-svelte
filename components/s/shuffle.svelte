<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psv830b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="psv830b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:shuffle" {...props}></Icon>
