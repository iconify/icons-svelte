<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf8j2-5ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf8j2-5ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trulia" {...props}></Icon>
