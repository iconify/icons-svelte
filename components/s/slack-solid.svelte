<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byal_6bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byal_6bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:slack-solid" {...props}></Icon>
