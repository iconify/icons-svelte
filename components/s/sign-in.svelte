<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb9885b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="hb9885b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-in" {...props}></Icon>
