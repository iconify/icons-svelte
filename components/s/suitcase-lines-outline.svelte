<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns8ydacjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ns8ydacjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-lines-outline" {...props}></Icon>
