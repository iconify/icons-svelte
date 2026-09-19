<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up7yltm1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up7yltm1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:traffic-barrier" {...props}></Icon>
