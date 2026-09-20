<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsm1_jstp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm1_jstp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tubes-sharp" {...props}></Icon>
