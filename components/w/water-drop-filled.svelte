<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwcbthb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwcbthb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-drop-filled" {...props}></Icon>
