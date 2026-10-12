<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clchgpbjo.css';
import '../../css/q/qvo2fwbpx.css';
import '../../css/r/rmh8yimxi.css';
import '../../css/w/wq8vaxb7s.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="clchgpbjo"/><path class="qvo2fwbpx"/><path class="rmh8yimxi"/><path class="wq8vaxb7s"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-meter-check-48-bold" {...props}></Icon>
