<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9nmjxl7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9nmjxl7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-line" {...props}></Icon>
