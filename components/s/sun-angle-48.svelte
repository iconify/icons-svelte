<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_49f5bfn.css';
import '../../css/o/oz7q2qb4l.css';
import '../../css/q/qxq5b3bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_49f5bfn"/><path class="oz7q2qb4l"/><path class="qxq5b3bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-angle-48" {...props}></Icon>
