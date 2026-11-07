<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmxa02b4w.css';
import '../../css/t/tllmdybix.css';
import '../../css/o/ojkge583k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmxa02b4w"/><path class="tllmdybix"/><path class="ojkge583k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-heart-bold-duotone" {...props}></Icon>
