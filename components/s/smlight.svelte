<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh0rzjbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh0rzjbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smlight" {...props}></Icon>
