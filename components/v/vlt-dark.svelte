<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok9hfbanf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":175};
const content = `<path class="ok9hfbanf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vlt-dark" {...props}></Icon>
