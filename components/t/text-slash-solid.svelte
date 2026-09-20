<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsg_f3idp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsg_f3idp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:text-slash-solid" {...props}></Icon>
