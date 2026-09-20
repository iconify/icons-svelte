<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akm5fqd2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akm5fqd2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-search-outline" {...props}></Icon>
