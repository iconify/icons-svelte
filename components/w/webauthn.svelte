<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j97522bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j97522bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webauthn" {...props}></Icon>
