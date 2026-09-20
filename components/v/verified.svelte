<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc2xgcdyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tc2xgcdyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:verified" {...props}></Icon>
