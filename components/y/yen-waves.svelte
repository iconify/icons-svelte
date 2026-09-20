<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgv23sbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgv23sbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-waves" {...props}></Icon>
