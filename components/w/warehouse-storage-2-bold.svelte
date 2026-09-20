<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muv-rs82u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muv-rs82u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:warehouse-storage-2-bold" {...props}></Icon>
