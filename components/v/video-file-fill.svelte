<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vxvpbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9vxvpbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:video-file-fill" {...props}></Icon>
