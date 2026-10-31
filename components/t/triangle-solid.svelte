<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfknb81as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfknb81as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:triangle-solid" {...props}></Icon>
