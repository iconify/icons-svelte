<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo32ugb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo32ugb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scraparr-dark" {...props}></Icon>
