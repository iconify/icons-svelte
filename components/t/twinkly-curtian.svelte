<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpsqq_b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpsqq_b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-curtian" {...props}></Icon>
