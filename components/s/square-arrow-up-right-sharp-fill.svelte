<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpa2y2bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpa2y2bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-up-right-sharp-fill" {...props}></Icon>
