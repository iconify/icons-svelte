<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp-_yub6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp-_yub6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sennheiser" {...props}></Icon>
