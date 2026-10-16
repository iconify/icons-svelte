<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snsrwjb2q.css';
import '../../css/a/a35pl3byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="snsrwjb2q"/><path class="a35pl3byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermistor-48" {...props}></Icon>
