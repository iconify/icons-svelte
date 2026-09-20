<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur5wd60bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur5wd60bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xpla" {...props}></Icon>
