<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyzz4-b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyzz4-b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-econic" {...props}></Icon>
