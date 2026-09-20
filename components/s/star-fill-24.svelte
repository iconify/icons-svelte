<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqmpk3elo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqmpk3elo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:star-fill-24" {...props}></Icon>
