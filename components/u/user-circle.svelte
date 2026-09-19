<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxliwubgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxliwubgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:user-circle" {...props}></Icon>
