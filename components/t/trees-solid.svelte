<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nozoseb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nozoseb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trees-solid" {...props}></Icon>
