<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzrryjb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzrryjb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:suitcase-3" {...props}></Icon>
