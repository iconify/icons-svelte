<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hax9i4bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hax9i4bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tree-palm-solid" {...props}></Icon>
