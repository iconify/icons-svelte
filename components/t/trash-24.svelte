<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq3da4h7l.css';
import '../../css/s/slygv4qud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq3da4h7l"/><path class="slygv4qud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:trash-24" {...props}></Icon>
