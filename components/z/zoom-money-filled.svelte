<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytcgqdivm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcgqdivm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-money-filled" {...props}></Icon>
