<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6gxh7bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6gxh7bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tulip" {...props}></Icon>
