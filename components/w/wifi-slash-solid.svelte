<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2r_4cczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2r_4cczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:wifi-slash-solid" {...props}></Icon>
