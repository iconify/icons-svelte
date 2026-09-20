<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4so3qlya.css';
import '../../css/l/lsxdb1s3e.css';
import '../../css/c/cyj7fswlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4so3qlya"/><path class="lsxdb1s3e"/><circle class="cyj7fswlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-pages-ltr" {...props}></Icon>
