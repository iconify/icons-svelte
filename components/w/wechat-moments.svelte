<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr3a83odw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kr3a83odw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wechat-moments" {...props}></Icon>
