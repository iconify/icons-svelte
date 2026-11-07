<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3cwxfump.css';
import '../../css/h/ho371t52a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cwxfump"/><path class="ho371t52a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-bottom-up-outline" {...props}></Icon>
