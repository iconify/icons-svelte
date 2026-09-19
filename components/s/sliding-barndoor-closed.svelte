<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-8wivbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-8wivbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sliding-barndoor-closed" {...props}></Icon>
