<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkgk9qbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkgk9qbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tm" {...props}></Icon>
