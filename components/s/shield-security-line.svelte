<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy3dp1yll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy3dp1yll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-security-line" {...props}></Icon>
