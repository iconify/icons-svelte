<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmguok5nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmguok5nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-down-left-solid" {...props}></Icon>
