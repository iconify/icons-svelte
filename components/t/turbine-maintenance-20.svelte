<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bygov5bnk.css';
import '../../css/c/cgej8yb_k.css';
import '../../css/v/v1mu2tbzf.css';
import '../../css/i/id-912baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bygov5bnk"/><path class="cgej8yb_k"/><path class="v1mu2tbzf"/><path class="id-912baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:turbine-maintenance-20" {...props}></Icon>
