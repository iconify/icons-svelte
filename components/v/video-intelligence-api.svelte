<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfzc8lbfq.css';
import '../../css/s/si00v7b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzc8lbfq"/><path class="si00v7b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:video-intelligence-api" {...props}></Icon>
