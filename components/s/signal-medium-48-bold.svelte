<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd-5y7buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cd-5y7buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-medium-48-bold" {...props}></Icon>
