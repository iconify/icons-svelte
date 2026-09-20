<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi7e1ubdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7e1ubdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tasklist-24" {...props}></Icon>
