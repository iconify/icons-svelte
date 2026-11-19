<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay1d6pr1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay1d6pr1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skoda-peaq" {...props}></Icon>
