<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl21qac3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vl21qac3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-arabic-latin" {...props}></Icon>
