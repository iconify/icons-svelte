<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilhl5o__u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilhl5o__u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wind" {...props}></Icon>
