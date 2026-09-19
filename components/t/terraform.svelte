<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3wm-mdki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i3wm-mdki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:terraform" {...props}></Icon>
