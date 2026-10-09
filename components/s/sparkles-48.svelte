<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxx2r1bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vxx2r1bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkles-48" {...props}></Icon>
