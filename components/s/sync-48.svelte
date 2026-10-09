<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0duj3ble.css';
import '../../css/x/x3wc924xj.css';
import '../../css/i/i1s8y7e8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i0duj3ble"/><path class="x3wc924xj"/><path class="i1s8y7e8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sync-48" {...props}></Icon>
