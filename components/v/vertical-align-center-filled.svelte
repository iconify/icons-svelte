<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebuhi1bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebuhi1bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-align-center-filled" {...props}></Icon>
