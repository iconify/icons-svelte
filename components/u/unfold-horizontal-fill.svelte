<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldyunebeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldyunebeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unfold-horizontal-fill" {...props}></Icon>
