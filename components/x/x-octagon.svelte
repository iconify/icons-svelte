<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-j_jbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-j_jbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-octagon" {...props}></Icon>
