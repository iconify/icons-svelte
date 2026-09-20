<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xemmwkqtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xemmwkqtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:route-off-sharp" {...props}></Icon>
