<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9rzpk0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="hx9rzpk0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:wrench" {...props}></Icon>
