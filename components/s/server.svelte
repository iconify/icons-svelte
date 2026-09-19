<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlko4hp7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":580,"height":684};
const content = `<path class="hlko4hp7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:server" {...props}></Icon>
