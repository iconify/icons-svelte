<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-44i5b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-5.5};
const content = `<path class="y-44i5b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:strikethrough" {...props}></Icon>
