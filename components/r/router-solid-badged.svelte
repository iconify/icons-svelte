<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmt7zh78e.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged vmt7zh78e"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-2--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:router-solid-badged" {...props}></Icon>
