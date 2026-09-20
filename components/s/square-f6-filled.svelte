<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4_ru7a0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4_ru7a0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f6-filled" {...props}></Icon>
