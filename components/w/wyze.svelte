<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl6niib_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl6niib_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wyze" {...props}></Icon>
