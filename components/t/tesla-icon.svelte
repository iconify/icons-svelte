<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hukx58fwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hukx58fwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-icon" {...props}></Icon>
