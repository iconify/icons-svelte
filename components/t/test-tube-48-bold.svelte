<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siepju6rr.css';
import '../../css/o/o2a3vtbnh.css';
import '../../css/p/p6ygvpb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="siepju6rr"/><path class="o2a3vtbnh"/><path class="p6ygvpb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:test-tube-48-bold" {...props}></Icon>
