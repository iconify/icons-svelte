<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwqhfdsoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqhfdsoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-text-solid" {...props}></Icon>
