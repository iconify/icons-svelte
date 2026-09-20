<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luemwubey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luemwubey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:yoshi" {...props}></Icon>
