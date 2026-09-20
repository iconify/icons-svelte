<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g037_eb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g037_eb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search3" {...props}></Icon>
