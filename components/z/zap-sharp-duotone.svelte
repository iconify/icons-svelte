<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lknj651ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lknj651ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:zap-sharp-duotone" {...props}></Icon>
