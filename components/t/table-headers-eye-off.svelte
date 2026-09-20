<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k534gcbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k534gcbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-headers-eye-off" {...props}></Icon>
