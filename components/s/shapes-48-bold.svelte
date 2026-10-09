<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sok4o7bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sok4o7bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shapes-48-bold" {...props}></Icon>
