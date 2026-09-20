<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spy95v0su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spy95v0su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:share-line" {...props}></Icon>
