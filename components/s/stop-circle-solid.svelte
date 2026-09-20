<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b911mpgha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b911mpgha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:stop-circle-solid" {...props}></Icon>
