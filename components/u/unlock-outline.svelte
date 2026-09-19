<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax45mqb4h.css';
import '../../css/i/i6wr-kbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax45mqb4h"/><path class="i6wr-kbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:unlock-outline" {...props}></Icon>
