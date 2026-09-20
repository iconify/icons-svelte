<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6y_s-uod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6y_s-uod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-security-filled" {...props}></Icon>
