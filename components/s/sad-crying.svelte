<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk7xh8b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk7xh8b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sad-crying" {...props}></Icon>
