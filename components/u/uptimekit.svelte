<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkei5sq7u.css';
import '../../css/q/qy8hd1btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkei5sq7u"/><path class="qy8hd1btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimekit" {...props}></Icon>
