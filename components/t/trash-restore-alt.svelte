<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmgly0bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gmgly0bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:trash-restore-alt" {...props}></Icon>
