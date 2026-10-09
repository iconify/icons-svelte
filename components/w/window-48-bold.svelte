<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0at87b5x.css';
import '../../css/e/esgmmdbyu.css';
import '../../css/e/e4bwz0btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m0at87b5x"/><path class="esgmmdbyu"/><path class="e4bwz0btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:window-48-bold" {...props}></Icon>
