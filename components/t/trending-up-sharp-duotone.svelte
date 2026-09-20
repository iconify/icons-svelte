<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2e4psbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2e4psbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-up-sharp-duotone" {...props}></Icon>
