<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3vimybge.css';
import '../../css/n/nhqseef_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3vimybge"/><path class="nhqseef_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-bold" {...props}></Icon>
