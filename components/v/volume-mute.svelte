<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7zvab3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oc7zvab3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:volume-mute" {...props}></Icon>
