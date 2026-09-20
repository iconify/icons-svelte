<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n47b7099b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n47b7099b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-libra" {...props}></Icon>
