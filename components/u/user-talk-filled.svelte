<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw_3-n8mp.css';
import '../../css/x/xu9n3sboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_3-n8mp"/><path class="xu9n3sboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-talk-filled" {...props}></Icon>
