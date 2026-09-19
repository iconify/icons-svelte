<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-9p8b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fp-9p8b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:todoist" {...props}></Icon>
