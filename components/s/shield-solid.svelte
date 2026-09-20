<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3rd5ebba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3rd5ebba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-solid" {...props}></Icon>
