<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol_hlwb8r.css';
import '../../css/n/n1uzpgbmf.css';
import '../../css/z/zxuwimbur.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged ol_hlwb8r"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged n1uzpgbmf"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged zxuwimbur"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:vm-outline-badged" {...props}></Icon>
