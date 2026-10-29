<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig7r6rpsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig7r6rpsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stop-solid" {...props}></Icon>
