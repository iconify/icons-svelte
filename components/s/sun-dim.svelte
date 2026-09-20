<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq7oig01j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq7oig01j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sun-dim" {...props}></Icon>
