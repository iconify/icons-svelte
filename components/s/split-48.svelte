<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbqw8r0sh.css';
import '../../css/r/r_zfy8bnu.css';
import '../../css/q/qpbeuubxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wbqw8r0sh"/><path class="r_zfy8bnu"/><path class="qpbeuubxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:split-48" {...props}></Icon>
