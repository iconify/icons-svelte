<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknvjuxat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sknvjuxat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wine-glass-filled" {...props}></Icon>
