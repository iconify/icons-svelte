<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0otgbc0o.css';
import '../../css/z/zh6xcri0n.css';
import '../../css/t/tsmhkwu9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0otgbc0o"/><path clip-rule="evenodd" class="zh6xcri0n"/><path class="tsmhkwu9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:school-filled" {...props}></Icon>
