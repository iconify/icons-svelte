<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwv8wbscl.css';
import '../../css/m/m7s0i2b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwv8wbscl"/><path class="m7s0i2b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:space-24" {...props}></Icon>
