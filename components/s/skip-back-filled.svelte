<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_xmtbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7_xmtbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:skip-back-filled" {...props}></Icon>
