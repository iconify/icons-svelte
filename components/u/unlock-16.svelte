<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd96l610s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kd96l610s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:unlock-16" {...props}></Icon>
