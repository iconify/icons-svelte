<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_oqwdk7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b_oqwdk7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:speech-bubble-exclamation" {...props}></Icon>
