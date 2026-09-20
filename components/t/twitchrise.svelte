<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_9emp3jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_9emp3jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitchrise" {...props}></Icon>
