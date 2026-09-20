<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdmf3g-ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zdmf3g-ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-wafinder-sink-wash-clean-toilet-bathroom-water" {...props}></Icon>
