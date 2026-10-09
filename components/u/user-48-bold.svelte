<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftb-bce_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ftb-bce_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-48-bold" {...props}></Icon>
