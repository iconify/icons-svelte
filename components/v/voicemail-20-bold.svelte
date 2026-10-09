<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czj819b3o.css';
import '../../css/l/lh6vhf69p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czj819b3o"/><path class="lh6vhf69p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voicemail-20-bold" {...props}></Icon>
