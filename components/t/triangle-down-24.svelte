<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlhawqkmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlhawqkmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-down-24" {...props}></Icon>
