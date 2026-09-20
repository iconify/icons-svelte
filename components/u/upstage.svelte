<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr7sejb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr7sejb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:upstage" {...props}></Icon>
