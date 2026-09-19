<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loibq93je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loibq93je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-candies-hearts" {...props}></Icon>
