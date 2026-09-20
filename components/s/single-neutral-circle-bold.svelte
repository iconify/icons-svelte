<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1b4wbhw.css';
import '../../css/i/ialwtkkcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1b4wbhw"/><path class="ialwtkkcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-circle-bold" {...props}></Icon>
