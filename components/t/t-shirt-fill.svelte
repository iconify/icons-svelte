<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tehthnb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tehthnb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-fill" {...props}></Icon>
