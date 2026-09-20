<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5itd_45v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5itd_45v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:thingiverse" {...props}></Icon>
