<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjafqbcjo.css';
import '../../css/l/lnd6titzq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qjafqbcjo"/><path class="clr-i-outline clr-i-outline-path-2 lnd6titzq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tablet-line" {...props}></Icon>
