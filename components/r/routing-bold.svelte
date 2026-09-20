<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra9-jw9gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra9-jw9gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-bold" {...props}></Icon>
