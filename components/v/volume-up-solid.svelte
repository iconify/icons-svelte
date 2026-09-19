<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzz9jcdew.css';
import '../../css/e/eler63bmi.css';
import '../../css/e/euyepzwwh.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 mzz9jcdew"/><path class="clr-i-solid clr-i-solid-path-2 eler63bmi"/><path class="clr-i-solid clr-i-solid-path-3 euyepzwwh"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:volume-up-solid" {...props}></Icon>
