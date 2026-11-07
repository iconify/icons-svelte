<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaizi48jf.css';
import '../../css/t/ty867ghkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path class="ty867ghkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minus-bold-duotone" {...props}></Icon>
