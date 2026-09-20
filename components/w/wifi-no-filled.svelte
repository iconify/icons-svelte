<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4sop7z6r.css';
import '../../css/b/b5ugqsb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4sop7z6r"/><path class="b5ugqsb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wifi-no-filled" {...props}></Icon>
