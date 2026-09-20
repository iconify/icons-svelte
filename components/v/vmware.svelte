<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqre6ibnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqre6ibnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vmware" {...props}></Icon>
