<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vai96navg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vai96navg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sync-slash" {...props}></Icon>
