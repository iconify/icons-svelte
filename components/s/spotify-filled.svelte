<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v524kibsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v524kibsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:spotify-filled" {...props}></Icon>
