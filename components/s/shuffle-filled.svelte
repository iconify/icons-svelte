<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqngrw5ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqngrw5ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shuffle-filled" {...props}></Icon>
