<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzhq8ujm.css';
import '../../css/m/mdm2icu2v.css';
import '../../css/o/oc6ekbbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwzhq8ujm"/><path clip-rule="evenodd" class="mdm2icu2v"/><path class="oc6ekbbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-alpha-desc-16" {...props}></Icon>
