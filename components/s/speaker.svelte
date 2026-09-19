<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmkin6x6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmkin6x6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:speaker" {...props}></Icon>
