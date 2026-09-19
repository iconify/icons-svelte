<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp06jhbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp06jhbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-skype" {...props}></Icon>
