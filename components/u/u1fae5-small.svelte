<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ia12bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l9ia12bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1fae5-small" {...props}></Icon>
