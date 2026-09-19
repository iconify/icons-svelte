<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1t4lm0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md1t4lm0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:slack-old" {...props}></Icon>
