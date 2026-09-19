<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v76w70e2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v76w70e2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:route" {...props}></Icon>
