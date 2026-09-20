<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufuc2cbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufuc2cbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safety-certificate-fill" {...props}></Icon>
