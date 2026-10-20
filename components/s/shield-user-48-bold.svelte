<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce0cywmuu.css';
import '../../css/c/cmhn4ab9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0cywmuu"/><path class="cmhn4ab9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-user-48-bold" {...props}></Icon>
