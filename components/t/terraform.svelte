<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b07gwsbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":458,"height":512};
const content = `<path class="b07gwsbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:terraform" {...props}></Icon>
