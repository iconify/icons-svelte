<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zri1lgb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zri1lgb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:triangle" {...props}></Icon>
