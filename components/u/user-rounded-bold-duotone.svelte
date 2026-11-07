<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0nhpsynn.css';
import '../../css/r/rarrkzbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><ellipse class="rarrkzbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-rounded-bold-duotone" {...props}></Icon>
