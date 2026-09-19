<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahhe4s6pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahhe4s6pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yaml-alt1" {...props}></Icon>
