<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxt8g5bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxt8g5bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webauthn" {...props}></Icon>
