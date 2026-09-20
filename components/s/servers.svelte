<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwr6g16yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwr6g16yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:servers" {...props}></Icon>
