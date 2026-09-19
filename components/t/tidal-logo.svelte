<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjmi7louc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjmi7louc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tidal-logo" {...props}></Icon>
