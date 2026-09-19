<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfbh3cbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfbh3cbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stroke-bottom" {...props}></Icon>
