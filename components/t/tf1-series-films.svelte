<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la0kt7buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la0kt7buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tf1-series-films" {...props}></Icon>
