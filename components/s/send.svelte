<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_ly38gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="il_ly38gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:send" {...props}></Icon>
