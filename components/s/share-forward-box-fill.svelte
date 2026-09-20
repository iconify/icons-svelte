<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiuto9r3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiuto9r3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-forward-box-fill" {...props}></Icon>
