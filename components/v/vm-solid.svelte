<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_uptrb-m.css';
import '../../css/v/vuogqwbrj.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="a_uptrb-m clr-i-solid clr-i-solid-path-1"/><path class="clr-i-solid clr-i-solid-path-2 vuogqwbrj"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:vm-solid" {...props}></Icon>
