<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j54ttfgtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j54ttfgtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-slash-24" {...props}></Icon>
