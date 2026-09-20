<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is--5bbuk.css';
import '../../css/l/lkmselk-n.css';
import '../../css/l/lsxdb1s3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is--5bbuk"/><path class="lkmselk-n"/><path class="lsxdb1s3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:special-pages-ltr" {...props}></Icon>
