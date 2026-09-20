<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6gtnxgyh.css';
import '../../css/g/gsv3t-buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z6gtnxgyh"/><path class="gsv3t-buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:trash" {...props}></Icon>
