<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqa3gbhnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqa3gbhnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:thumbsdown-24" {...props}></Icon>
