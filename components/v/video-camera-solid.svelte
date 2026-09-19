<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9hqm9bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9hqm9bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:video-camera-solid" {...props}></Icon>
