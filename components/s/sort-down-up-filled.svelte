<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgvaycp0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgvaycp0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-down-up-filled" {...props}></Icon>
