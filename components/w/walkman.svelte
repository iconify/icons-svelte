<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g85bdcbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g85bdcbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:walkman" {...props}></Icon>
