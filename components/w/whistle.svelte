<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8u9h8b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8u9h8b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:whistle" {...props}></Icon>
