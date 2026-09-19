<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmwwk298f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmwwk298f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:seal-check-filled" {...props}></Icon>
