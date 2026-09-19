<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-_9kbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg-_9kbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-settings-filled" {...props}></Icon>
