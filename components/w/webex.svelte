<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvbyww8rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvbyww8rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webex" {...props}></Icon>
