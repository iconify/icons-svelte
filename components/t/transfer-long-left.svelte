<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h64dolbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h64dolbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-long-left" {...props}></Icon>
