<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qga2a08ds.css';
import '../../css/j/j7p4iebhi.css';
import '../../css/y/yeqg2frrd.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged qga2a08ds"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged j7p4iebhi"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged yeqg2frrd"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:upload-cloud-outline-badged" {...props}></Icon>
