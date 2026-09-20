<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzq4r8brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzq4r8brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:youtube" {...props}></Icon>
