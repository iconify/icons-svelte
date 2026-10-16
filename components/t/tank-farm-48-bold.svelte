<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5b617bur.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o5b617bur"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tank-farm-48-bold" {...props}></Icon>
