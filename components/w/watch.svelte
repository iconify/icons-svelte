<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w99c1bbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w99c1bbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:watch" {...props}></Icon>
