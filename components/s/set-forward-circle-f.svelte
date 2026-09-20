<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_5zdtjim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="i_5zdtjim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-forward-circle-f" {...props}></Icon>
