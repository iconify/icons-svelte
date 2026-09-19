<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_vranuey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_vranuey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-chrome-outline" {...props}></Icon>
