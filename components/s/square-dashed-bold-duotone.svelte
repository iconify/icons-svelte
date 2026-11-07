<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2sk80bby.css';
import '../../css/f/fbnpbdb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2sk80bby"/><path class="fbnpbdb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-dashed-bold-duotone" {...props}></Icon>
