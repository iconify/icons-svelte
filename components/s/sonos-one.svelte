<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa3tn266q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3tn266q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-one" {...props}></Icon>
