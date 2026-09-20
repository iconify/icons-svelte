<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0e2mrbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0e2mrbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tuxedo-computers" {...props}></Icon>
