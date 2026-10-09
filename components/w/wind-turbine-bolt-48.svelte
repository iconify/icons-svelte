<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3kxc0e1n.css';
import '../../css/y/y8netlxfj.css';
import '../../css/f/foaw4bimw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i3kxc0e1n"/><path class="y8netlxfj"/><path class="foaw4bimw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-bolt-48" {...props}></Icon>
