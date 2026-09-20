<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x323-x_4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x323-x_4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:zoom-in" {...props}></Icon>
