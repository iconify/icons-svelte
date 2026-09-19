<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5wt1ab4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5wt1ab4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:siren-filled" {...props}></Icon>
