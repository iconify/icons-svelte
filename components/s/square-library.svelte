<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v40n-8bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v40n-8bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-library" {...props}></Icon>
