<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxpexwnur.css';
import '../../css/r/rpjhj7j4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":152,"height":152};
const content = `<path class="fxpexwnur"/><path class="rpjhj7j4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:todoist" {...props}></Icon>
