<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfky40b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfky40b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:traffic-light-solid" {...props}></Icon>
