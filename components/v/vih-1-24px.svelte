<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1k85xbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1k85xbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vih-1-24px" {...props}></Icon>
