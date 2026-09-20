<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua4o1w2iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua4o1w2iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send2-filled" {...props}></Icon>
