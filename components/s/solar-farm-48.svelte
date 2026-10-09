<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1xv4fk9e.css';
import '../../css/k/kf0yeki3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a1xv4fk9e"/><path class="kf0yeki3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-farm-48" {...props}></Icon>
