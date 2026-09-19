<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2llityiz.css';
import '../../css/g/g7hfw0b6x.css';
import '../../css/h/hqofnceah.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 s2llityiz"/><path class="clr-i-solid clr-i-solid-path-2 g7hfw0b6x"/><path class="clr-i-solid clr-i-solid-path-3 hqofnceah"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:target-solid" {...props}></Icon>
