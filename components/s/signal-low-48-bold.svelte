<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9sm63b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9sm63b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-low-48-bold" {...props}></Icon>
