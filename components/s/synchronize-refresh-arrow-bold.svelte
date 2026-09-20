<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3cr_w9fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cr_w9fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:synchronize-refresh-arrow-bold" {...props}></Icon>
