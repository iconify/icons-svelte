<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uww47e16f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uww47e16f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:send-alt-02-filled" {...props}></Icon>
