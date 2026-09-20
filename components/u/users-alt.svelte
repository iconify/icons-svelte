<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz5zlkbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz5zlkbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:users-alt" {...props}></Icon>
