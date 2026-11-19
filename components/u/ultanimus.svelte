<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2n198b7o.css';
import '../../css/x/xeh2z5bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":20,"left":3,"top":2};
const content = `<path class="o2n198b7o"/><circle class="xeh2z5bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ultanimus" {...props}></Icon>
