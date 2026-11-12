<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8vvxucjh.css';
import '../../css/x/xvp3f-_7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8vvxucjh"/><path class="xvp3f-_7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tailscale-light" {...props}></Icon>
