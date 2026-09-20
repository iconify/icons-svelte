<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uumr8ibws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uumr8ibws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:social-off" {...props}></Icon>
