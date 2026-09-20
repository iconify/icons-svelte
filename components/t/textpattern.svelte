<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy35qbymc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy35qbymc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:textpattern" {...props}></Icon>
