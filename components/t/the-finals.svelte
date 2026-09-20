<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svu75sbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svu75sbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-finals" {...props}></Icon>
