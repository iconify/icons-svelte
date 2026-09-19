<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak4665b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak4665b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:samsung-serif" {...props}></Icon>
