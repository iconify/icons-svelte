<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9zde8_tk.css';
import '../../css/z/zj6og8p4y.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 g9zde8_tk"/><circle class="clr-i-outline clr-i-outline-path-2 zj6og8p4y" transform="rotate(-45 27.132 27.092)"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:wrench-line" {...props}></Icon>
