<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awui1tb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awui1tb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rtlzwei" {...props}></Icon>
