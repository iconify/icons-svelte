<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_7-qbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il_7-qbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-mighty" {...props}></Icon>
