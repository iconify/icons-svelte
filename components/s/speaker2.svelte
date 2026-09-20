<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh5jy1blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nh5jy1blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speaker2" {...props}></Icon>
