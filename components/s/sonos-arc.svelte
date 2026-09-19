<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeq7jyr0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeq7jyr0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-arc" {...props}></Icon>
