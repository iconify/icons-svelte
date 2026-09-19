<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aim5hzbvg.css';
import '../../css/e/e4iey6k0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aim5hzbvg"/><path class="e4iey6k0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:usb" {...props}></Icon>
