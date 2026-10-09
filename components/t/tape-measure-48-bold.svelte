<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8g73tbef.css';
import '../../css/k/kui6b9bke.css';
import '../../css/y/yzh_ltb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u8g73tbef"/><path class="kui6b9bke"/><path class="yzh_ltb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tape-measure-48-bold" {...props}></Icon>
