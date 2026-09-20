<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t22_x14sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t22_x14sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sage" {...props}></Icon>
