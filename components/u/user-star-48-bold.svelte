<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x89zfmb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x89zfmb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-star-48-bold" {...props}></Icon>
