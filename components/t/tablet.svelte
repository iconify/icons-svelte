<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga5axac9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":850};
const content = `<path class="ga5axac9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:tablet" {...props}></Icon>
