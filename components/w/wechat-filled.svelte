<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e89cb6bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e89cb6bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wechat-filled" {...props}></Icon>
