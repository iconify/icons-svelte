<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh-wf7b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-wf7b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:styleshare" {...props}></Icon>
