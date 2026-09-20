<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afagcqcga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afagcqcga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-none" {...props}></Icon>
