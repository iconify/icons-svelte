<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfv6q6btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfv6q6btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:trash-fill" {...props}></Icon>
