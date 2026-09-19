<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq0rzh6os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq0rzh6os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vert-blind-open" {...props}></Icon>
