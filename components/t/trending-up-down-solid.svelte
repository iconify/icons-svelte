<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghyd-h94s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghyd-h94s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trending-up-down-solid" {...props}></Icon>
