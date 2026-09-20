<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxd2ugikm.css';
import '../../css/v/vhi06qdng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zxd2ugikm"/><path class="vhi06qdng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:zoom-horizontal-16" {...props}></Icon>
