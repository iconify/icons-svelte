<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8qmuvb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x8qmuvb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:unlocked-fill-20" {...props}></Icon>
