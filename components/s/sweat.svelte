<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk-2f43fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk-2f43fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sweat" {...props}></Icon>
