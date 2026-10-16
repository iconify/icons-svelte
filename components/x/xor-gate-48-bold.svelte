<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kllrszb1h.css';
import '../../css/q/q6laauggs.css';
import '../../css/d/d3uhlcbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kllrszb1h"/><path class="q6laauggs"/><path class="d3uhlcbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:xor-gate-48-bold" {...props}></Icon>
