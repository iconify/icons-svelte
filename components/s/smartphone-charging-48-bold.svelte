<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svb9bze3d.css';
import '../../css/m/mfy25ks6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="svb9bze3d"/><path class="mfy25ks6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-charging-48-bold" {...props}></Icon>
