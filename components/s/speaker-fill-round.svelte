<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbw5gmbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbw5gmbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:speaker-fill-round" {...props}></Icon>
