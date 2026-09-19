<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmy7obc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmy7obc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-candies-pearl" {...props}></Icon>
