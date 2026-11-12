<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4cpj7cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cf4cpj7cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sshwifty-light" {...props}></Icon>
