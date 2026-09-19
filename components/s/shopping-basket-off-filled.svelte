<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ds8_m2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2ds8_m2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-basket-off-filled" {...props}></Icon>
