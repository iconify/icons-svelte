<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3s97wwwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3s97wwwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zdf" {...props}></Icon>
